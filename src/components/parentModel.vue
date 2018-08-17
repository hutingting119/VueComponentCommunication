<template>
  <div id="demo">
    <childModel v-model="str"></childModel>
    <span>{{str}}</span>
  </div>
</template>
<script>
import childModel from './childModel.vue'
export default {
  data () {
    return {
      str: 'hello'
    }
  },
  components: {
    childModel
  }
}
</script>
