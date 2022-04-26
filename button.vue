<script>
  export default {
    data() {
      return {
        count: 0,
      }
    },
    methods: {
      increment(){
        this.count++
      }
    }
  }
</script>

<template>
  <button>
    {{count}}
  </button>
</template>
