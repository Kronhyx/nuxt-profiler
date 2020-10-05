<template>
  <ToolbarMask variant="warning">
    <template #default>
      <MaskLabel>7882</MaskLabel>
      <MaskValue>ms</MaskValue>
    </template>
    <template #info>
      <MaskPiece label="Total time">7780 ms</MaskPiece>
      <MaskPiece label="Initialization time">596 ms</MaskPiece>
    </template>
  </ToolbarMask>
</template>

<script lang="ts">
import { Component, Vue } from 'nuxt-property-decorator'
import MaskValue from './_label.vue'
import ToolbarMask from './_mask.vue'
import MaskLabel from './_value.vue'
import MaskPiece from './_piece.vue'

@Component({ components: { ToolbarMask, MaskLabel, MaskValue, MaskPiece } })
export default class ToolbarTime extends Vue {

}
</script>

<style lang="scss" scoped>

</style>
