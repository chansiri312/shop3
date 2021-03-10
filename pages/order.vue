<template>
  <div>
    <nab />
    <div class="container">
      <O1 />
    </div>
    
  </div>
</template>

<script>
import O from '~/components/O1.vue'
import nab from '~/components/navbar.vue'

export default {
  components: {
    O,
    nab,
  },
}
</script>