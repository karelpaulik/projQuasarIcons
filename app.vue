<template>
  <div>
    <div><q-icon name="thumb_up" size="md" color="teal" /></div>
  </div>
</template>

<script setup>
  import { useQuasar } from 'quasar'
  const $q = useQuasar()
  console.log($q.iconSet)
</script>