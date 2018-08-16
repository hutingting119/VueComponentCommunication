<template>
  <div>
    <child-component1></child-component1>
    <child-component2></child-component2>
    <button v-on:click="showChildComponentData">显示子组件的数据</button>
  </div>
</template>

<script>
export default{
  components: {
    'child-component1': {
      template: '<p>I am ok</p>',
      data: function () {
        return {
          msg: 'child component 111111'
        }
      }
    },
    'child-component2': {
      template: '<p>ok</p>',
      data: function () {
        return {
          msg: 'child component 222222'
        }
      }
    }
  },
  methods: {
    showChildComponentData: function () {
      for (var i = 0; i < this.$children.length; i++) {
        alert(this.$children[i].msg)
      }
    }
  }
}
</script>
