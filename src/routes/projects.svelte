<script>
	import ProjectCard from './_projectCard.svelte';
</script>

<div style="margin-bottom: -0.25rem">Some of my</div>
<h1>Side Projects</h1>

<div class="grid">
	<ProjectCard
		title="create.party"
		url="https://create.party"
		description="Little helper for organizing your events."
		stack="Sveltekit, TailwindCSS, Firebase, Vercel"
	>
		<img
			slot="icon"
			src="https://create.party/favicon.svg"
			style="height: 1.5rem; margin-right: 0.5rem;"
			alt="create.party logo"
		/>
	</ProjectCard>

	<ProjectCard
		title="samu.bar"
		url="https://samu.bar"
		description="Tiny serverless URL shortener"
		stack="Sveltekit, New.css, Cloudflare Workers, Cloudflare KV"
	>
		<img
			slot="icon"
			src="https://samu.bar/favicon.svg"
			style="height: 1.5rem; margin-right: 0.5rem;"
			alt="samu.bar logo"
		/>
	</ProjectCard>
</div>
<div class="grid">
	<ProjectCard
		title="json2table"
		url="https://json2table.bach.to"
		description="View your JSON data in an interactive table and share it with others without ever storing data on server side."
		stack="Svelte, Tabulator"
	>
		<div slot="icon" style="font-size: 1rem; margin-right: 0.5rem;  display: inline-block">➡️</div>
	</ProjectCard>
	<ProjectCard
		title="phoenixbin"
		url="https://phoenixbin.herokuapp.com"
		description="Inspect HTTP requests coming to a custom endpoint. Helpful for web hook trigger debugging."
		stack="Elixir, Phoenix, TachyonsCSS, Heroku"
	>
		<img
			slot="icon"
			src="https://phoenixbin.herokuapp.com/favicon.ico"
			style="height: 1.5rem; margin-right: 0.5rem;"
			alt="phoenixbin logo"
		/>
	</ProjectCard>
</div>
<div class="grid">
	<ProjectCard
		title="citychurch-ulm.de"
		url="https://citychurch-ulm.de"
		description="Website of a local church in Ulm. Custom theme and backoffice for scheduling events and organizing sunday service volunteers."
		stack="KirbyCMS, TachyonsCSS"
	>
		<img
			slot="icon"
			src="https://citychurch-ulm.de/favicon.ico"
			style="height: 1.5rem; margin-right: 0.5rem;"
			alt="citychurch-ulm logo"
		/>
	</ProjectCard>
	<ProjectCard
		title="Trackerle"
		url="https://trackerle.vercel.app/"
		description="Easily keep track of your working time across devices and see weekly/monthly hours easily."
		stack="Svelte, TailwindCSS, Firestore"
	>
		<img
			slot="icon"
			src="https://trackerle.vercel.app/favicon.svg"
			style="height: 1.5rem; margin-right: 0.5rem;"
			alt="citychurch-ulm logo"
		/>
	</ProjectCard>
</div>
<div class="grid">
	<ProjectCard
		title="Pairing Timer"
		url="https://samuba.github.io/pairing-timer"
		description="A remote ready, pair programming timer that tells you when to switch drivers."
		stack="Svelte, TailwindCSS, FirebaseDB"
	>
		<img
			slot="icon"
			src="https://samuba.github.io/pairing-timer/favicon.ico"
			style="height: 1.5rem; margin-right: 0.5rem;"
			alt="citychurch-ulm logo"
		/>
	</ProjectCard>
	<ProjectCard
		title="Logomat 3000"
		url="https://logomat3000.glitch.me/"
		description="A tool for german speech therapist's to quickly find words to use during the therapy."
		stack="JQuery, TachyonsCSS, Glitch.com"
	>
		<img
			slot="icon"
			src="https://gomix.com/favicon-app.ico"
			style="height: 1.5rem; margin-right: 0.5rem;"
			alt="logomat logo"
		/>
	</ProjectCard>
</div>
