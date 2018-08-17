<template>
    <div>
      <childCom></childCom>
    </div>
</template>

<script>
export default{
  data: function () {
    return {
      msg: 'this is parent'
    }
  },
  components: {
    'childCom': {
      template: '<button @click="shouParentData">button</button>',
      methods: {
        shouParentData: function () {
          alert(this.$parent.msg)
        }
      }
    }
  }
}
</script>
