<template>
  <v-flex xs6>
    <v-card class="card--flex-toolbar">
      <v-toolbar card class="light-blue">
        <v-toolbar-title class="white--text">Send Tokens</v-toolbar-title>
      </v-toolbar>
      <v-list>
        <v-list-tile>
          <v-list-tile-title>
            To Address
          </v-list-tile-title>
          <v-list-tile-content>
  
            <v-text-field label="0x00" single-line v-model="addr"></v-text-field>
  
          </v-list-tile-content>
        </v-list-tile>
  
        <v-list-tile>
          <v-list-tile-title>
            Amount
          </v-list-tile-title>
          <v-list-tile-content>
  
            <v-text-field label="0.00" single-line v-model="amount"></v-text-field>
  
          </v-list-tile-content>
        </v-list-tile>
  
        <v-list-tile>
  
          <v-spacer></v-spacer>
  
          <v-list-tile-action>
            <v-btn primary dark>Send</v-btn>
          </v-list-tile-action>
        </v-list-tile>
  
      </v-list>
  
    </v-card>
  </v-flex>
</template>
<script>
import config from '../config'

export default {
  data () {
    return {
      addr: null,
      amount: null,
      wallet: null
    }
  },

  methods: {
  }
}
</script>

