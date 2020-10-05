<template>
  <div class="sf-toolbar-block sf-toolbar-block-request">
    <a href="https://flexy.ftwo.local/_profiler/3346c2?panel=request">
      <div class="sf-toolbar-icon">
        <slot></slot>
        <span class="sf-toolbar-value sf-toolbar-info-piece-additional">
          <slot name="value">slot value</slot>
        </span>
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
import { Component, Vue } from 'nuxt-property-decorator'

@Component({})
export default class ToolbarMask extends Vue {

  get routeName() {
    return this.$route.name
  }

}
</script>

<style lang="scss" scoped>

.sf-toolbar-block {
  cursor: default;
  display: block;
  float: left;
  height: 36px;
  margin-right: 0;
  white-space: nowrap;
}

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
