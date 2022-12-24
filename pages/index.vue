<template>
  <div style="font-family: 'Mulish', sans-serif;" class="bg-white">
    <Navbar/>
    <Partner/>
    <Features/>
    <PriceTag/>
    <Tutorial/>
  </div>
</template>

<script>
import Features from '../components/Features.vue'
export default {
  components: { Features },
  name: 'IndexPage'
}
</script>

