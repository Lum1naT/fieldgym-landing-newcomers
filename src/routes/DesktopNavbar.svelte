<script>
    import '../styles/desktopNavbar.scss';
	function scrollIntoView({ target }) {
		const el = document.querySelector(target.getAttribute('href'));
		if (!el) return;
    el.scrollIntoView({
      behavior: 'smooth'
    });
  }
</script>

<div class="container-fluid d-none d-lg-flex" id="desktop-navbar">
	<nav class="navbar">
				<div class="container-fluid">
				<a class="navbar-brand" href="/">
					<img src="favicon.svg" alt="logo" width="80" height="80" class="d-inline-block align-text-bottom">
					<span class="company-name m-5 font-acetone">FIELD GYM</span>
				</a>
				<div class="nav-fill">
					<a  href="#section-bjj" on:click|preventDefault={scrollIntoView}>BJJ</a>
					<a  href="#section-2" on:click|preventDefault={scrollIntoView}>MMA</a>
					<a  href="#section-3" on:click|preventDefault={scrollIntoView}>Bojové Sporty</a>
				</div>
				</div>


	</nav>

</div>

<style>

	</style>