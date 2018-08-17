<template>
    <div>
      <button @click="toParent">to parent</button>
    </div>
</template>

<script>
export default{
  methods: {
    toParent: function () {
      this.$emit('chiToPar', 'this is childe')
    }
  }
}
</script>
