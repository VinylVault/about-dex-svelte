<script lang="ts">
	import Header from '$lib/header/Header.svelte';
	import '../app.css';
	import sveltelogo from '../lib/header/svelte-logo.svg';
	import twitchlogo from '../lib/header/twitch-official.svg';
</script>

<Header />

<main>
	<slot />
</main>

<footer>
	<p>&copy; 2022 Rich Codes Web, All Rights Reserved</p>
	<p>This website was coded on
		<a href="https://www.twitch.tv/dexvinyl">
			<img src={twitchlogo} alt="Twitch" />
		</a>
		using
		<a href="https://kit.svelte.dev">
			<img src={sveltelogo} alt="SvelteKit" />
		</a>
		Svelte & SvelteKit</p>
</footer>

<style>
	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		max-width: 1024px;
		margin: 0 auto;
		box-sizing: border-box;
	}

	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 40px;
	}

	footer a {
		font-weight: bold;
	}

	.corner {
		height: 3em;
	}

	.corner a {
		display: flex;
		align-items: center;
		justify-content: center;
		width: 100%;
		height: 100%;
	}

	footer img {
		width: 2em;
		height: 2em;
		object-fit: contain;
	}


	@media (min-width: 480px) {
		footer {
			padding: 40px 0;
		}
	}
</style>
