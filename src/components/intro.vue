<template>
  <parallax>
    <div class="intro-body">
			<div class="intro-section">

			</div>
      
    </div>
  </parallax>
</template>

<script>
  export default {
    name: 'it Intro',
  }
</script>

<style lang="scss" scoped>
  @import '../styles/variables';

  .intro-body {
    height: 100vh;
    width: 100%;
    background: linear-gradient(
								to right top,
							rgba(188, 0, 255, 0.7),
							rgba(76, 15, 204, 0.7)),
								url(../assets/img/1.jpg);
							
    background-size: 100% 100%;
    // animation: introGradient 8s ease infinite;
    // -webkit-animation: introGradient 8s ease infinite;
    // -moz-animation: introGradient 8s ease infinite;
  }

  // @keyframes introGradient {
  //   0% {
  //     background-position: 87% 0%
  //   }
  //   50% {
  //     background-position: 14% 100%
  //   }
  //   100% {
  //     background-position: 87% 0%
  //   }
  // }

</style>
