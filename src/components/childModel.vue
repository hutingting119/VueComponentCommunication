<template>
  <span>
      <input  :value="value" @input="$emit('chilM', $event.target.value)">
  </span>
</template>
<script>
export default {
  data () {
    return {
    }
  },
  props: ['value'],
  model: {
    prop: 'value',
    event: 'chilM'
  }
}
</script>
