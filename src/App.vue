<template>
  <div id="app">
    <router-view/>
    <HeaderComponent/>
    <MainComponent />
    <FooterComponent/>
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent'
import MainComponent from './components/MainComponent'
import FooterComponent from './components/FooterComponent'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    MainComponent,
    FooterComponent
  }
}
</script>

<style lang="scss">

</style>
