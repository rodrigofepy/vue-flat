<template>
  <div id="app">
    <tag-component text="example text"></tag-component>
    <btn />
    <vflat-footer :fixed="true">
      Vue Flat Footer
    </vflat-footer>
  </div>
</template>

<script>
import { tagComponent, btn, vflatFooter } from './index'
export default {
  name: 'app',
  components: {
    tagComponent,
    btn,
    vflatFooter
  }
}
</script>
