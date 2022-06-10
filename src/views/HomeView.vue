<template>
  <div class="home">
    <HeaderSection/>
    <NewArrival/>
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderSection from '@/components/HeaderSection.vue'
import NewArrival from '@/components/NewArrival.vue'

export default {
  name: 'HomeView',
  components: {
    HeaderSection,
    NewArrival
  }
}
</script>

