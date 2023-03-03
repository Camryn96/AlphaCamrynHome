<template>
<div class="NavBar">
	<nav>
    <router-link to="/home"><img src="https://img.icons8.com/ios-filled/50/null/home-page.png"/>Home</router-link> |
    <router-link to="/About"><img src="https://img.icons8.com/external-tanah-basah-glyph-tanah-basah/48/null/external-about-social-media-ui-tanah-basah-glyph-tanah-basah.png"/>About Us</router-link> |
    <router-link to="./Contact"><img src="https://img.icons8.com/ios-filled/50/null/question-mark.png"/>Contact Us</router-link> |
    <router-link to="/Products"><img src="https://img.icons8.com/external-kiranshastry-solid-kiranshastry/64/null/external-games-gaming-kiranshastry-solid-kiranshastry.png"/>Products</router-link> |
    <router-link to="/Login"><img src="https://img.icons8.com/ios-filled/50/null/login-rounded-right.png"/>Login/Register</router-link> |
    <router-link to="/Admin"><img src="https://img.icons8.com/ios-filled/50/null/administrator-male--v1.png"/>Admin</router-link> 
  </nav>
  <router-view/>
</div>
	</template>
	<script>
	
	export default{
		// eslint-disable-next-line vue/multi-word-component-names
		name:'NavBar'
	}
	</script>