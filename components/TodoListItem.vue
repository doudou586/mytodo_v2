<template>
  <li>
    {{ todo.text  }}__({{todo.id}})
    <button @click="$emit('remove', todo.id)">
      -
    </button>
  </li>
</template>

<script>
export default {
  props: {
    todo: {
      type: Object,
      required: true
    }
  }
}
</script>