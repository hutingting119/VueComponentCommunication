<template>
  <div class="hello">
    <!--<parentTem></parentTem>-->
    <!--<parentRef></parentRef>-->
    <!--<parentChild></parentChild>-->
    <!--<childProp></childProp>-->
    <childParent></childParent>
  </div>
</template>

<script>
import parentTem from './parentTem.vue'
import parentRef from './parentRef.vue'
import parentChild from './parentChild.vue'
import childProp from './childProp.vue'
import childParent from './childParent.vue'
export default {
  name: 'HelloWorld',
  components: {
    parentTem,
    parentRef,
    parentChild,
    childProp,
    childParent
  }
}
</script>
