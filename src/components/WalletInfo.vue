<template>
  <v-flex xs6>
    <v-card class="card--flex-toolbar">
      <v-toolbar card class="light-blue">
        <v-toolbar-title class="white--text">My Wallet</v-toolbar-title>
      </v-toolbar>
      <v-list>
        <v-list-tile>
          <v-list-tile-title>
            Address
          </v-list-tile-title>
          <v-list-tile-content>
            {{ coinbase }}
          </v-list-tile-content>
        </v-list-tile>
  
        <v-list-tile>
          <v-list-tile-title>
            Eth Balance
          </v-list-tile-title>
          <v-list-tile-content>
            {{ balance }}
          </v-list-tile-content>
        </v-list-tile>
  
        <v-list-tile>
          <v-list-tile-title>
            Token Balance
          </v-list-tile-title>
          <v-list-tile-content>
            {{ tokens }}
          </v-list-tile-content>
        </v-list-tile>
  
      </v-list>
  
    </v-card>
  </v-flex>
</template>
<script>

export default {
  data () {
    return {
      coinbase: 0x00,
      balance: 0,
      tokens: 0
    }
  },

  mounted () {

  },

  methods: {
  }
}
</script>

