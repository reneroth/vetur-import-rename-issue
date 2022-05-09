<template>
  <div>
    {{ fo }}
  </div>
</template>

<script>
import * as _ from 'lodash'
import Foobar from './Foobar.vue'

export default {
  props: ['foo', 'bar'],
  components: {
    Foobar,
  },
}
</script>