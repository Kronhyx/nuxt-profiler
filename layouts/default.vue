<template>
  <div>
    <Nuxt />
    <Toolbar />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'nuxt-property-decorator'
import Toolbar from '~/components/toolbar.vue'

@Component({ components: { Toolbar } })
export default class DefaultLayout extends Vue {

}
</script>
