<script lang="coffee">
> @8p/full:Full
  @8p/lang/Lang.svelte

# ./Search.svelte
</script>

<template lang="pug">
//- Search
aside
  Full
  Lang
</template>

<style lang="stylus">
@media (max-width 560px)
  aside
    display flex
    justify-content space-between
    width 100%

    &>:global(i:last-child)
      margin-right 0 !important
</style>

