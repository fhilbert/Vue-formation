<script setup>
import TodoForm from "./TodoForm.vue";
import TodoList from "./TodoList.vue";
</script>

<template>
	<div>
		<div class="todo-app">
			<h1>To Do List</h1>
			<todo-form />
			<todo-list />
		</div>
	</div>
</template>
<style scoped>
.todo-app {
	color: black;
	padding: 5vh;
	min-height: 100vh;
	width: 30vw;
	background-color: #f7f9fc;
}
</style>
