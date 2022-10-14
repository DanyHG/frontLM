<template>
  <v-app id="inspire">
    <Drawer />
    <v-main>
      <nuxt />
    </v-main>
  </v-app>
</template>

<script>
import Drawer from '~/components/dashboard/drawer.vue'
export default {
  components: {
    Drawer
  }
}
</script>
