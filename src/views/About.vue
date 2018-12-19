<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>

<script>
  export default {
    name: 'about',
    data () {
      return {

      }
    },
    mounted() {
      let func = () => {
        console.log(+ new Date)
      }
      func()
    },
  }
</script>

<style scoped lang="scss">
  .about {
    h1 {
      background: linear-gradient(-45deg, #FE8727 0em, #FE8727 0.9em, #FE4500 1em, #FE4500 2.1em, #FE8727 2.1em, #FE8727 2.9em, #FE4500 3em);
    }
  }
</style>