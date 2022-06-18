<template>
  <q-page class="row items-center justify-evenly">
    <DumpValue :val="{foo: 'blah'}" />
  </q-page>
</template>

<script lang="ts" setup>
import DumpValue from 'components/DumpValue.vue'
</script>
