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
			</ul>
		</nav>
	</header>

	<slot />

	<footer />
</main>
