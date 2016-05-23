<template>
  <div class="form-group">
    <label class="col-sm-4 control-label">{{ title }}</label>
    <div class="col-sm-8">
      <input type="text" class="form-control" placeholder="{{ description }}" v-model="shared.inputValue">
    </div>
  </div>
</template>

<script>
import * as shared from './../Data'

export default {
  data () {
    shared.default.inputValue = 'Default text'

    return {
      title: 'Form Input',
      description: 'You should write something in here',
      shared: shared.default
    }
  }
}
</script>