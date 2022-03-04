<template>
  <div id="app">
    <appHeader/>
    <router-view/>
    <appFooter/>
  </div>
</template>

<script>
// @ is an alias to /src
import appHeader from '@/components/appHeader.vue'
import appFooter from '@/components/appFooter.vue'

export default {
  components: {
    appFooter,
    appHeader
  }
}
</script>
