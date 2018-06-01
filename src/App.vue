<template>
  <div id="app">
    <Intro></Intro>
    <Footer></Footer>
    <router-view/>
  </div>
</template>

<script>
  import Intro from './components/intro';
  import Footer from './components/footer';
  import Main from './components/main';

  export default {
    name: 'App',
    components: {
			Intro, 
			Main, 
			Footer
		}
  }

</script>

<style lang="scss">
  @import './styles/variables';

* {
    padding: 0;
		margin: 0;
		box-sizing: border-box;
	}
	html { overflow-y: hidden; }
  #app {
    font-family: 'Roboto', sans-serif;
    text-align: center;
    color: $main-color;
    margin: 0;
		padding: 0;
	}
	
</style>
