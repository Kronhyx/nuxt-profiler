<template>
  <div class="sf-toolbar-block" :class="variantClass">
    <a href="https://flexy.ftwo.local/_profiler/3346c2?panel=request">
      <div class="sf-toolbar-icon">
        <slot></slot>
      </div>
    </a>
    <div class="sf-toolbar-info">
      <div class="sf-toolbar-info-group">
        <slot name="info">slot info</slot>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'nuxt-property-decorator'

@Component({})
export default class ToolbarMask extends Vue {
  @Prop({ default: null, type: String }) readonly variant!: string

  get variantClass() {
    return `status status-${this.variant}`
  }
}
</script>

<style lang="scss" scoped>

.status {
  color: #FFF;

  &.status-success {
    background-color: #4F805D;
  }

  &.status-warning {
    background-color: #A46A1F;
  }

  &.status-danger {
    background-color: #B0413E;
  }
}

</style>
