<template>
    <div>
      <childRef ref="child"></childRef>
      <button @click="change">change</button>
    </div>
</template>

<script>
import childRef from './childRef.vue'
export default{
  components: {
    childRef
  },
  methods: {
    change: function () {
      this.$refs.child.str = 'world'
    }
  }
}
</script>
