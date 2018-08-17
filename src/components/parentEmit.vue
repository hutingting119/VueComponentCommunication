<template>
    <div>
      <div>{{str}}</div>
      <childEmit @chiToPar="updateStr" :sendDate="str"></childEmit>
    </div>
</template>

<script>
import childEmit from './childEmit.vue'
export default{
  data () {
    return {
      str: 'this is parent'
    }
  },
  components: {
    childEmit
  },
  methods: {
    updateStr: function (data) {
      this.str = data
    }
  }
}
</script>
