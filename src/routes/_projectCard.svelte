<script lang="ts">
	export let title: string;
	export let url: string;
	export let description: string;
	export let stack: string;
</script>

<article>
	<header>
		<a href={url} target="_blank">
			<slot name="icon" />
			{title}
		</a>
	</header>
	{description}
	<div style="margin-top: 0.5rem;">
		<u>Stack:</u>
		{stack}
	</div>
</article>

<style>
	article {
		margin-bottom: 0.5rem;
		margin-top: 0.5rem;
	}
</style>
