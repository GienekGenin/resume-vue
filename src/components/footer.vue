<template>
	<div class="footer-fixed">
		<p>faAwesome</p>
	</div>
</template>

<script>
  export default {
    name: "footer"
  }
</script>

<style lang="scss" scoped>
  @import '../styles/variables';

  .footer-fixed {
		position: fixed;
		bottom: 0;
		left: 0;
		width: 100%;
		background-color: rgba(207, 189, 189, 0.6);
	}
</style>
