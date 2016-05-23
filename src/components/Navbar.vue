<template>
  <nav class="navbar navbar-default">
    <div class="container">
      <div class="navbar-header">
        <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
          <span class="sr-only">Toggle navigation</span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
        </button>
        <a class="navbar-brand" href="/">
          <img class="vue-logo" src="./../assets/logo.png" height="25" />
        </a>
      </div>
      <div id="navbar" class="collapse navbar-collapse">
        <ul class="nav navbar-nav">
          <li class="active"><a href="#">Home</a></li>
        </ul>
        <form class="navbar-form navbar-right">
          <language-selection></language-selection>
        </form>
      </div>
    </div>
  </nav>
</template>

<script>
import LanguageSelection from './specials/LanguageSelection'

export default {
  components: {
    LanguageSelection
  }
}
</script>