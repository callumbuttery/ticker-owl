<template>
  <div>
    <v-card>
      <v-navigation-drawer permanent>
        <v-list class="ma-4">
          <v-list-item>
            <v-list-item-content>
              <v-icon color="green"> mdi-chart-line </v-icon>
              <v-list-item-subtitle class="text-md-center mt-2"
                >+10%</v-list-item-subtitle
              >
              <v-list-item-subtitle class="text-center mt-1"
                >Market Performance</v-list-item-subtitle
              >
            </v-list-item-content>
          </v-list-item>
        </v-list>

        <v-divider></v-divider>

        <v-list nav class="ml-4">
          <v-list-item link>
            <v-list-item-icon>
              <v-icon>mdi-domain</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Stock Watch</v-list-item-title>
          </v-list-item>
          <v-list-item link>
            <v-list-item-icon>
              <v-icon>mdi-currency-btc</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Crypto Watch</v-list-item-title>
          </v-list-item>
          <v-list-item link>
            <v-list-item-icon>
              <v-icon>mdi-database-search</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Market Search</v-list-item-title>
          </v-list-item>
          <v-list-item link>
            <v-list-item-icon>
              <v-icon>mdi-database-search</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Index Tracker</v-list-item-title>
          </v-list-item>
          <v-list-item link>
            <v-list-item-icon>
              <v-icon>mdi-database-search</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Ticker Performance</v-list-item-title>
          </v-list-item>
          <v-list-item link>
            <v-list-item-icon>
              <v-icon>mdi-database-search</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Coin Performance</v-list-item-title>
          </v-list-item>
        </v-list>
      </v-navigation-drawer>
    </v-card>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
};
</script>
