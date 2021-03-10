<template>
  <div>
    <nab />
     <H1 />
  </div>
</template>

<script>
import H1 from '~/components/H1.vue'
import nab from '~/components/navbar.vue'

export default {
  components: {
    H1,
    nab,
  },
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
