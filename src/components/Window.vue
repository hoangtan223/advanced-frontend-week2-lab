<template>
  <div class="container">
    <HeadingPanel/>
    <ContentPanel/>
  </div>
</template>

<script>

import HeadingPanel from './HeadingPanel'
import ContentPanel from './ContentPanel'

export default {
  name: 'Window',
  components: {
    HeadingPanel,
    ContentPanel
  }
}
</script>

<style>

</style>
