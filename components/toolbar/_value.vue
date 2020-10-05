<template>
  <span class="sf-toolbar-value">
    <slot>slot value</slot>
  </span>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'nuxt-property-decorator'

@Component({})
export default class MaskValue extends Vue {
  @Prop({ default: null, type: String }) readonly variant!: string

  get variantClass() {
    return `status status-${this.variant}`
  }
}
</script>
