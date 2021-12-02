<script lang="ts">
</script>

<main class="container">
	<header>
		<nav>
			<ul>
				<li><strong>Bach.to</strong></li>
			</ul>
			<ul>
				<li><a sveltekit:prefetch href="/projects">Projects</a></li>
				<li><a sveltekit:prefetch href="/">About</a></li>
				<li><a href="https://www.linkedin.com/in/samuel-bach-53404a129/" target="_blank">CV</a></li>
			</ul>
		</nav>
	</header>

	<slot />

	<footer style="height: 7rem;">
		<br />
	</footer>
</main>
