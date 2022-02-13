<script lang="ts">
	import Header from '$lib/header/Header.svelte';
	import sveltelogo from '../lib/header/svelte-logo.svg';
	import twitchlogo from '../lib/header/twitch-official.svg';
	import '../app.css';
</script>

<Header />

<main>
	<slot />
</main>

<footer>
	<p class="footer-text">&copy; 2022 Rich Codes Web, All Rights Reserved</p>
	<p class="footer-text">This website was coded LIVE on
		<a href="https://www.twitch.tv/RichCodesWeb" target="_blank">
			<img src={twitchlogo} alt="Twitch" />
		</a>
		using
		<a href="https://kit.svelte.dev" target="_blank">
			<img src={sveltelogo} alt="SvelteKit" />
		</a>
		SvelteKit</p>
</footer>

<style>
	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		max-width: 1080px;
		margin: 0 auto;
		box-sizing: border-box;
	}

	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}

	.footer-text {
	@apply flex items-center justify-center align-middle;
	}

	.footer-text img {
	@apply px-2 align-middle;
	width:3rem;
	height:3rem;
	}

	footer a {
		font-weight: bold;
	}


	@media (min-width: 480px) {
		footer {
			padding: 40px 0;
		}
	}
</style>
