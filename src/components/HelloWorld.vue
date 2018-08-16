<template>
  <div class="hello">
    <parentTem></parentTem>
  </div>
</template>

<script>
import parentTem from './parentTem.vue'
export default {
  name: 'HelloWorld',
  components: {
    parentTem
  }
}
</script>
