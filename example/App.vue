<template>
  <ElDesignForm ref="markForm"/>
</template>
<script>
import json from './default.json'
export default {
  mounted() {
    this.setForm()
  },
  methods: {
    setForm() {
      this.$refs.markForm.setJson(json)
    }
  }
}
</script>
