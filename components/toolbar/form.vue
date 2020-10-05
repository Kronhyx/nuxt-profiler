<template>
  <ToolbarMask>
    <template #default>
      <MaskValue>
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
          <path fill="#AAA" d="M20.5 4H18V2.5c0-.8-.7-1.5-1.5-1.5h-9C6.7 1 6 1.7 6 2.5V4H3.5C2.7 4 2 4.7 2 5.5v16c0 .8.7 1.5 1.5 1.5h17c.8 0 1.5-.7 1.5-1.5v-16c0-.8-.7-1.5-1.5-1.5zM9 4h6v1H9V4zm10 16H5V7h1.1c.2.6.8 1 1.4 1h9c.7 0 1.2-.4 1.4-1H19v13zm-2-9c0 .6-.4 1-1 1H8c-.6 0-1-.4-1-1s.4-1 1-1h8c.6 0 1 .4 1 1zm0 3c0 .6-.4 1-1 1H8c-.6 0-1-.4-1-1s.4-1 1-1h8c.6 0 1 .4 1 1zm-4 3c0 .6-.4 1-1 1H8c-.6 0-1-.4-1-1s.4-1 1-1h4c.6 0 1 .4 1 1z" />
        </svg>
      </MaskValue>
      <MaskLabel variant="info">1</MaskLabel>
    </template>
    <template #info>
      <MaskPiece label="Number of forms">1</MaskPiece>
      <MaskPiece label="Number of errors">0</MaskPiece>
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
export default class ToolbarForm extends Vue {

}
</script>

<style lang="scss" scoped>

</style>
