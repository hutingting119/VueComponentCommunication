<template>
  <div class="hello">
    <!--<parentTem></parentTem>-->
    <!--<parentRef></parentRef>-->
    <!--<parentChild></parentChild>-->
    <!--<childProp></childProp>-->
    <!--<childParent></childParent>-->
    <!--<parentModel></parentModel>-->
    <parentEmit></parentEmit>
  </div>
</template>

<script>
import parentTem from './parentTem.vue'
import parentRef from './parentRef.vue'
import parentChild from './parentChild.vue'
import childProp from './childProp.vue'
import childParent from './childParent.vue'
import parentModel from './parentModel.vue'
import parentEmit from './parentEmit.vue'
export default {
  name: 'HelloWorld',
  components: {
    parentTem,
    parentRef,
    parentChild,
    childProp,
    childParent,
    parentModel,
    parentEmit
  }
}
</script>
