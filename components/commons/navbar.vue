<template>
	<div>
		<header id="header" class="mui-bar mui-bar-nav">
			<a class="mui-action-back mui-icon mui-icon-left-nav mui-pull-left" @click="goback"></a>
			<h1 class="mui-title">{{title}}</h1>
		</header>
	</div>
</template>
<script type="text/javascript">
	export default {
		props:['title'],
		methods:{
			goback(){
				this.$router.go(-1);
			}
		}
	}
</script>
<style type="text/css"></style>