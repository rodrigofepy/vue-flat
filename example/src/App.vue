<template>
  <div id="app">
    <tag-component text="example text"></tag-component>
    <btn />
  </div>
</template>

<script>
import { tagComponent, btn } from '../../src/index'
export default {
  name: 'app',
  components: {
    tagComponent,
    btn
  }
}
</script>
