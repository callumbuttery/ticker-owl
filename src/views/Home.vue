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

        <v-list nav class="ml-4" v-for="item in items" :key="item.title">
          <v-list-item link>
            <v-list-item-icon>
              <v-icon>{{ item.icon }}</v-icon>
            </v-list-item-icon>
            <v-list-item-title>{{ item.title }}</v-list-item-title>
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
  data() {
    return {
      items: [
        {
          title: "Stock Watch",
          icon: "mdi-domain",
          color: "green",
        },
        {
          title: "Crypto Watch",
          icon: "mdi-currency-btc",
          color: "green",
        },
        {
          title: "Index Tracker",
          icon: "mdi-database-search",
          color: "green",
        },
        {
          title: "Stock Performers",
          icon: "mdi-chart-line",
          color: "green",
        },
        {
          title: "Crypto Performers",
          icon: "mdi-chart-line",
          color: "green",
        },
      ],
    };
  },
};
</script>
