<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'
import JumboApp from './components/JumboApp.vue'
import AppMenu from './components/AppMenu.vue'
import AppList from './components/AppList.vue'


export default {
  name: 'App',
  components: {
    AppHeader,
    AppMain,
    AppFooter,
    JumboApp,
    AppMenu,
    AppList,
  
  }
}
</script>

<template>
  <AppHeader/>
  <JumboApp/>
  <AppMenu/>
  <AppList/>
  <AppMain/>
  <AppFooter/>
</template>

<style lang="scss">
@import './styles/general.scss'
</style>
