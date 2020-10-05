<template>
  <span class="sf-toolbar-value">
    <slot>slot value</slot>
  </span>
</template>

<script lang="ts">
import { Component, Vue } from 'nuxt-property-decorator'

@Component({})
export default class MaskValue extends Vue {

}
</script>
