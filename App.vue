<template>
	<div id="app">
		<h2>My Todo App!</h2>
		<TodoList/>
	</div>
</template>

<script>
import TodoList from './components/TodoList.vue'

export default {
	components: {
		TodoList
	}
}
</script>

