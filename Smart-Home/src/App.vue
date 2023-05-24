<template>
  <div id="app">
      <app-header />
      <b-container>
      <notification-sec />
      <temp-sec />
      <cont-sec />
      <footer-sec />
    <router-view/>
    </b-container>
  </div>
</template>
<script>
import AppHeader from '/components/AppHeader.vue'
import ContSec from '/components/sections/ContSec.vue'
import FooterSec from '/components/sections/FooterSec.vue'
import NotificationSec from '/omponents/sections/NotificationSec.vue'
import TempSec from '/components/sections/TempSec.vue'

export default {
  name: 'App',
  components: {
    AppHeader,
    NotificationSec,
    TempSec,
    ContSec,
    FooterSec,
    
  }
}
</script>
<style lang="scss">

</style>

