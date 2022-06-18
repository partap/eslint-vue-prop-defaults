<script setup lang="ts">
interface Props {
  val?: unknown
  flag?: boolean
}
const props = withDefaults(defineProps<Props>(), {
  flag: false
})

</script>
<template>
  <div>
    <div>Type: {{ typeof props.val }}</div>
    <div>Value: {{ JSON.stringify(props.val) }} </div>
  </div>
</template>
