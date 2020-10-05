<template>
  <span class="sf-toolbar-label">
    <slot>slot label</slot>
  </span>
</template>

<script lang="ts">
import { Component, Vue } from 'nuxt-property-decorator'

@Component({})
export default class MaskLabel extends Vue {

}
</script>
