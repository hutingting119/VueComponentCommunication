<template>
  <div class="hello">
    <!--<parentTem></parentTem>-->
    <parentRef></parentRef>
  </div>
</template>

<script>
import parentTem from './parentTem.vue'
import parentRef from './parentRef.vue'
export default {
  name: 'HelloWorld',
  components: {
    parentTem,
    parentRef
  }
}
</script>
