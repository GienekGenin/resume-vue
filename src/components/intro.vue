<template>
  
    <div class="MainContainer">

		<div class="ParallaxContainer">
			<h1>
				Alohfa!
			</h1>
		</div>

  	<div class="ContentContainer Skills">
    	<div class="Content">
      	<h1>
          Skills
        </h1>
        <div id="summary_skills">
          <h2>
            SUMMARY OF SKILLS:
          </h2>
          <ul>
            <li>Front-end Developer with X years of experience designing, developing, and managing complex e-commerce
              sites. Specializes in JS and responsive design
            </li>
            <li>Intermediate English level (written and spoken)</li>
            <li>Strong understanding of industry trends and content management systems</li>
            <li>Ability to improvise, learn new skills in short terms, self-motivated and result-oriented</li>
          </ul>
        </div>
        <div>
          <h2>TECHNICAL SKILLS:</h2>
          <ul>
            <li>Front-end: CSS3, HTML5, XML, web standards and accessibility, cross-browser compatibility, JSON with
              padding
            </li>
            <li>Programming/scripting languages: JavaScript (ES6, jQuery, Bootstrap), basic knowledge of SQL</li>
            <li>DB: Oracle</li>
            <li>Development tools: WebStorm, Note++, Sublime Text, Photoshop/Fireworks, GitHub Desktop</li>
            <li>APIs: Web Storage API, JSON API, Web-Storage API, Web Workers API, Geolocation API, Google Maps
              JavaScript API
            </li>
            <li>Version control systems: Git</li>
          </ul>
        </div>
      </div>
    </div><!--/Skills-->

		<div class="ParallaxContainer Projects">
    	<div class="Content">
				<h2>TECHNICAL SKILLS:</h2>
          <ul>
            <li>Front-end: CSS3, HTML5, XML, web standards and accessibility, cross-browser compatibility, JSON with
              padding
            </li>
            <li>Programming/scripting languages: JavaScript (ES6, jQuery, Bootstrap), basic knowledge of SQL</li>
            <li>DB: Oracle</li>
            <li>Development tools: WebStorm, Note++, Sublime Text, Photoshop/Fireworks, GitHub Desktop</li>
            <li>APIs: Web Storage API, JSON API, Web-Storage API, Web Workers API, Geolocation API, Google Maps
              JavaScript API
            </li>
            <li>Version control systems: Git</li>
          </ul>
			</div>
    </div><!--/Projects-->
		<div class="ContentContainer Contacts">
    	<div class="Content">
        <ul>
          <li>tel. +48 ********* Cell Phone</li>
          <li>Viber +48 ********** Viber</li>
          <li>Skype *********</li>
          <li>email ********.com</li>
          <li>Github www.github.com/*******</li>
          <li>facebook www.facebook.com/********</li>
          <li>location **************</li>
        </ul>
      </div>
    </div><!--/Contact-->
	</div><!-- /MainContainer -->
</template>

<script>
  export default {
    name: 'it Intro',
  }
</script>

<style lang="scss" scoped>
  @import '../styles/variables';



h1 {
  letter-spacing: -15px;
  font-family: Open Sans;
  color: white;
  text-align: center;
  font-size: 200px;
  font-weight: 800;
  line-height: 200px;
}

.MainContainer {
  perspective: 1px;
  transform-style: preserve-3d;
  height: 100vh;
  overflow-x: hidden;
  overflow-y: auto;
}

.ContentContainer {
  position: relative;
	display: block;
	z-index: 1;
}
		.Skills {
			height: 100vh;
			width: 100%;
			background: linear-gradient(240deg, #f5925d, #361c83);
		}
		.Projects {
			height: 100vh;
			width: 100%;
			background: linear-gradient(230deg, #78139e, #2f0ba8);
			
		}
		.Contacts {
			height: 100vh;
			width: 100%;
			background: linear-gradient(240deg, #384481,#5cddd9);
		}
		
.Content {
  max-width: 750px;
  margin: 0 auto;
  padding: 75px 0;
}

p {
  margin: 75px 0;
}

.ParallaxContainer {
  display: flex;
	flex: 1 0 auto;
	margin-left: -10px;
  position: relative;
  z-index: -1;
  height: 100vh;
  justify-content: center;
  align-items: center;
  transform: translateZ(-1px) scale(2);
  // background: url(https://www.toptal.com/designers/subtlepatterns/patterns/sakura.png);
	// background-color: rgb(250,228, 216);
	//linear-gradient(to right bottom,rgba(188, 0, 255, 0.7),rgba(76, 15, 204, 0.7)),url(../assets/img/1.jpg);
	background: url(../assets/img/trianglify.png);					
	background-size: cover;
	// -webkit-clip-path: polygon(0 0, 100% 0, 100% 76%, 0 95%);
	// clip-path: polygon(0 0, 100% 0, 100% 76%, 0 95%);
}

@import url('https://fonts.googleapis.com/css?family=Open+Sans:400,800');
  // .intro-body {
  //   animation: introGradient 8s ease infinite;
  //   -webkit-animation: introGradient 8s ease infinite;
  //   -moz-animation: introGradient 8s ease infinite;
  // }

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
