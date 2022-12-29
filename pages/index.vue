<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <portfolio />
    </v-col>
  </v-row>
</template>

<script>
import portfolio from '../components/portfolio.vue';
export default {
  name: 'IndexPage',
  components: {
    portfolio
  }
}
</script>
