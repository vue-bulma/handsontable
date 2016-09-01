<template>
  <div class="handsontable"></div>
</template>

<script>
import Handsontable from 'handsontable/dist/handsontable.full.js'

export default {

  props: {
    data: {
      type: Array,
      required: true,
      default: () = ([])
    },
    settings: {
      type: Object,
      default: () = ({})
    }
  },

  mounted() {
    this.settings.data = this.data
    this.table = new Handsontable(this.$el, this.settings)
  },

  beforeDestroy () {
    this.table.destroy()
  }

}
</script>

<style>
@import "~handsontable/dist/handsontable.full.css";
</style>

