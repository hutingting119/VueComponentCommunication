<template>
  <div>
    <child-component v-bind:str="str"></child-component>
  </div>
</template>

<script>
export default{
  data: function () {
    return {
      str: 'hello world'
    }
  },
  components: {
    'child-component': {
      props: ['str'],
      template: '<p>{{str}}</p>'
    }
  }
}
</script>
