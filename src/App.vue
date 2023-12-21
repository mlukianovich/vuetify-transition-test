<template>
  <v-card>
    <v-tabs
      bg-color="bg"
      color="primary"
    >
      <v-tab value="one">
        Item One
      </v-tab>
      <v-tab value="two">
        Item Two
      </v-tab>
      <v-tab value="three">
        Item Three
      </v-tab>
      <v-tab value="4">
        Lorem ipsum dolor sit.
      </v-tab>
      <v-tab value="5">
        Lorem ipsum dolor sit amet.
      </v-tab>
      <v-tab value="6">
        Lorem ipsum dolor sit amet consectetur.
      </v-tab>
    </v-tabs>
  </v-card>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
