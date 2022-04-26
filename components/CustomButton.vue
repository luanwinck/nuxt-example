<script>
  // import { useState } from '#app'

  export default {
    // setup() {
    //   const [count, setCount] = useState(0);

    //   const increment = () => {
    //     setCount(c => c + 1)
    //   }

    //   return {
    //     count,
    //     increment,
    //   }
    // }

    data() {
      return {
        count: 3,
        show: true,
      }
    },
    methods: {
      increment(){
        this.count++
      }
    },
    async fetch() {
      this.show = true
      setTimeout(() => {
        this.show = true
      }, 3000)
    }
  }
</script>

<template>
  <div>
    <span> Hello World {{count}} </span>
    <!-- <button v-on:click="increment">Incrementar</button> -->
    <button @click="increment">Incrementar 2</button>
  </div>
</template>
