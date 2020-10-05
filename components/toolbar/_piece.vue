<template>
  <div class="sf-toolbar-info-piece">
    <b>{{ label }}</b>
    <span>
      <slot></slot>
    </span>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'nuxt-property-decorator'

@Component({})
export default class MaskPiece extends Vue {
  @Prop({ required: true, type: String }) readonly label!: string

}
</script>
