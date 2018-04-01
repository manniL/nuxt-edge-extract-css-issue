<template>
  <div>
    <a/>
    <b/>
  </div>
</template>

<script>

export default {
  components: {
    A: () => import('~/components/A'),
    B: () => import ('~/components/B')
  }
}
</script>
