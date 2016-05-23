<template>
  <div class="form-group">
    <label class="col-sm-4 control-label">{{ title }}</label>
    <div class="col-sm-8">
      <select class="form-control"></select>
    </div>
  </div>	
</template>

<script>
export default {
  data () {
    return {
      title: 'Form Input',
      description: 'You should write something in here',
      value: 'Awesome!'
    }
  }
}
</script>