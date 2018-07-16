<template>
	<div id="app">
		<router-view/>
	</div>
</template>

<script>
	export default {
		name: 'App',
	};
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css?family=Nunito:400,400i,700');
#app {
	margin-top: 40px;
	font-family: 'Nunito', sans-serif;
}
tr {
	border: 1px solid #ccc;
}
.table thead {
	background: #f2f2f2;
	border-bottom: 1px solid #dee2e6;
}
</style>