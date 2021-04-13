<template>
  <v-app>
    <navigation />

    <bar />

    <carrosel />

    <footer-app />
  </v-app>
</template>

<script>
import Navigation from '@/components/Navigation'
import Bar from '@/components/Bar'
import Carrosel from '@/components/Carrosel'
import Footer from '@/components/Footer'

export default {
  components: {
    navigation: Navigation,
    bar: Bar,
    carrosel: Carrosel,
    footerApp: Footer
  },
  data() {
    return {

    }
  }
}
</script>
