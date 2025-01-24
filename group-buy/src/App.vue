
<template>
  <HeaderComponent />
  <SideBarComponent />

  <RouterView />
</template>

<script>
import { RouterLink, RouterView } from 'vue-router'
import HeaderComponent from '@/components/HeaderComponent.vue'
import SideBarComponent from '@/components/SideBarComponent.vue'

export default {
  components: {
    HeaderComponent, SideBarComponent, RouterView
  }

}

</script>

<style scoped>

</style>
