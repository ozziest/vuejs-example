<template>
  <h1>{{ message }}</h1>
</template>

<script>
import * as shared from './Data'

export default {
  data () {
    return {
      message: 'Hello World!',
      other: {
        user: {
          id: 1,
          email: 'i.ozguradem@gmail.com'
        }
      },
      shared: shared.default
    }
  }
}
</script>