<script>
    import '../styles/mobileNavbar.scss';
	function scrollIntoView({ target }) {
		const el = document.querySelector(target.getAttribute('href'));
		if (!el) return;
    el.scrollIntoView({
      behavior: 'smooth'
    });
  }
</script>

<div class="container-fluid d-lg-none" id="mobile-navbar">
	<nav class="navbar">

		<a href="#section-fight-sports" on:click|preventDefault={scrollIntoView}>Bojové sporty</a>
		<a href="#section-bjj" on:click|preventDefault={scrollIntoView}>BJJ</a>
		<a href="#section-mma" on:click|preventDefault={scrollIntoView}>MMA</a>



	</nav>

</div>

<style>


	</style>