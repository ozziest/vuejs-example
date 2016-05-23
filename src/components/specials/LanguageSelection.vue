<template>
  <select class="form-control" v-model="configurations.language">
    <option v-for="option in options" v-bind:value="option.value">
      {{ option.text }}
    </option>
  </select>
</template>

<script>
import * as shared from './../Data'

export default {
  data () {
    return {
      configurations: shared.default.configurations,
      options: shared.default.selects.languages
    }
  }
}
</script>