<template>
<div id="wrapper">
	<div id="canvasContainer"></div>
</div>
</template>

<script>
export default {
	name: 'container',
	mounted() {
    },
    methods: {
    }
};
</script>

<style lang="less">
html,
body {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
	background: #000000;
}
#wrapper {
	font-family: 'Avenir', Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
}
#wrapper::-webkit-scrollbar {
	display: none;
}
#wrapper{
    width: 100vw;
    height: 100vh;
    position: relative;
	overflow: hidden;
}
#canvasContainer {
    width: 100%;
    height: 100%;
}
</style>
