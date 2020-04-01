<template>
	<div>
		<div v-for="(todo,index) in todos" :key="index">
			{{todo.name}}
		</div>
	</div>
</template>

<script>
export default {
	 name: 'MyTodo',
	 props: {
	   todos: Array
	 }
}
</script>

<style>
</style>
