<template>
	<div id="AboutView">
		<NavBar/>
		<div class="About">
			<h1>About page:</h1>
		</div>
		<Footer/>


	</div>


	
</template>
<script>
import NavBar from '@/components/NavBar.vue'
import Footer from '@/components/Footer.vue'
export default{
	components:{
	NavBar,
	Footer
	}
}

</script>