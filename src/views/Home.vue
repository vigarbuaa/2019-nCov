<template>
  <div>
<home-header></home-header>
<home-navigation></home-navigation>
  </div>
</template>

<script>

import HomeHeader from '../components/header'
import HomeNavigation from '../components/navigation'
export default {
  name: 'Home',
  components: {
    HomeHeader,
    HomeNavigation
  }
}
</script>

<style lang="stylus" scoped>

</style>
