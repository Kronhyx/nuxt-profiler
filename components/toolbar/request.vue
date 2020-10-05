<template>
  <ToolbarMask>
    <template #default>
      <MaskLabel class="block">200</MaskLabel>
      <MaskValue>@</MaskValue>
      <MaskLabel>{{ $route.name }}</MaskLabel>
    </template>
    <template #info>
      <MaskPiece label="HTTP status">200 OK</MaskPiece>
      <MaskPiece label="Controller">ProductController :: editAction</MaskPiece>
      <MaskPiece label="Controller class">Flexy\Ftwo\Platform\Bundle\AdminBundle\Controller\ProductController</MaskPiece>
      <MaskPiece label="Route name">{{ $route.name }}</MaskPiece>
      <MaskPiece label="Has session">yes</MaskPiece>
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
export default class ToolbarRequest extends Vue {

}
</script>

<style lang="scss" scoped>
.block {
  color: #FFF;
  display: inline-block;
  font-size: 14px;
  height: 36px;
  line-height: 36px;
  padding: 0 10px;
  background-color: #4F805D;
}
</style>
