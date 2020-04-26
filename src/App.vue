<template>
  <div id="app">
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
    // helloworld
  },
  data() {
    return {
      a: 'aaa',
      b: 'bbb',
      c: 'ccc'
    }
  }
}
</script>

<style>

</style>
