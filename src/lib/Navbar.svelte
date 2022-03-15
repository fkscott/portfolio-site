<script>
    import { page } from '$app/stores';
    import '../../static/css/global.css'
</script>
<main>

    <div class="container-xxl">
		<nav class="navbar navbar-expand-lg navbar-light" id="navbar">
			<div class="container-fluid">
			  <a class="navbar-brand" href="/"><img src="./img/insignia.png" alt="header logo"></a>
			  <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
				<span class="navbar-toggler-icon"></span>
			  </button>
			  <div class="collapse navbar-collapse" id="navbarNav">
				<ul class="navbar-nav">

				  <li class="nav-item" id="home-link">
					<a class="nav-link {$page.url.pathname === '/' ? 'active': ''}"   href="/">home</a>
				  </li>

				  <li class="nav-item" id="about-link">
					<a class="nav-link {$page.url.pathname === '/about' ? 'active': ''}"   href="/about">about</a>
				  </li>

				  <li class="nav-item" id="projects-link">
					<a class="nav-link {$page.url.pathname === '/projects' ? 'active': ''}"  href="/projects">projects</a>
				  </li>
				</ul>
			  </div>
			</div>
		  </nav>

    </div>

</main>

<style>
	.navbar-nav a{
		font-family: 'HiriginoBold', sans-serif;
		font-size: 24pt;
		text-decoration: none;
		padding-inline: 30px;
	}

	.nav-link:hover{
		color:#4D91A8;
	}

	#home-link .active {
		color:#4D91A8;
	}

	#about-link .active {
		color:#4D91A8;
	}

	#projects-link .active {
		color:#4D91A8;
	}

	.navbar-brand img{
		width: 62px;
		height: auto;
	}
</style>