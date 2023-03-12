<script setup>
import { ref, onMounted, computed, watch } from 'vue'

const todos = ref([])
const name = ref('')

const input_content = ref('')
const input_category = ref(null)

const todos_asc = computed(() => {
  return todos.value.sort((a, b) => b.createdAt - a.createdAt)
})
</script>

<template>
  Hello
</template>


