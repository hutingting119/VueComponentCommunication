<template>
  <div class="hello">
    <!--<parentTem></parentTem>-->
    <!--<parentRef></parentRef>-->
    <parentChild></parentChild>
  </div>
</template>

<script>
import parentTem from './parentTem.vue'
import parentRef from './parentRef.vue'
import parentChild from './parentChild.vue'
export default {
  name: 'HelloWorld',
  components: {
    parentTem,
    parentRef,
    parentChild
  }
}
</script>
