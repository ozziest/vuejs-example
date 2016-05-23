<template>

  <navbar></navbar>

  <div class="container">

    <hello></hello>
    <p>
      Welcome to your Vue.js app!
      {{ languages }}
    </p>

    <h1>Form Elements</h1>
    <form class="form-horizontal">
      <ps-input></ps-input>
    </form>

  </div>

</template>

<script>
import Navbar from './components/Navbar'
import Hello from './components/Hello'
import PsInput from './components/inputs/PsInput'
import PsSelect from './components/inputs/PsSelect'

export default {
  components: {
    PsInput,
    PsSelect,
    Navbar,
    Hello
  }
}
</script>

<style>
@import '../node_modules/bootstrap/dist/css/bootstrap.css'
</style>
