<template>
  <div>
    <SVGIcons/>
    <HeaderComponent/>
    <HomeComponent/>
  </div>
</template>

<script>
import SVGIcons from './components/SVGIcons.vue'
import HeaderComponent from './components/HeaderComponent.vue'
import HomeComponent from './components/HomeComponent.vue'

export default {
  name: 'App',
  components: {
    SVGIcons,
    HeaderComponent,
    HomeComponent
  }
}
</script>

<style lang="scss">

</style>
