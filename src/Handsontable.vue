<template>
  <div class="handsontable"></div>
</template>

<script>
export default {
  props: {
    data: {
      type: Array,
      required: true,
      default: () => ([])
    },
    settings: {
      type: Object,
      default: () => ({})
    }
  },

  mounted () {
    this.settings.data = this.data
  },

  beforeDestroy () {
  }

}
</script>
