<script>
export default {
  data() {
    return {
      message: 'Hello World!'
    }
  },
  props:["name"]
}
</script>

<template>
  <h1>{{ message }}</h1>
</template>