<template>
  <div>
    <h1>Calculator</h1>
    <Display />
    <Buttons />
  </div>
</template>

<script>
import Display from "./components/Display"
import Buttons from "./components/Buttons"

export default {
  name: 'App',
  components: {
    Display,
    Buttons
  }
}
</script>

<style>

</style>
