<script context="module">
	import { browser, dev } from '$app/env';

	import './blog.css';
	// we don't need any JS on this page, though we'll load
	// it in dev so that we get hot module replacement...
	export const hydrate = dev;

	// ...but if the client-side router is already loaded
	// (i.e. we came here from elsewhere in the app), use it
	export const router = browser;

	// since there's no dynamic data here, we can prerender
	// it so that it gets served as a static asset in prod
	export const prerender = true;
</script>

<svelte:head>
	<title>Rich's Blog | RichCodesWeb</title>
</svelte:head>

<div class="content">
	<h1>Rich's Blog</h1>

<div class="portfolio">
	<div class="portfolio-item">
		<img style="width:100%;border:1px solid black;" src="/static/tvv21.jpg" alt="Website Design Is Under Cover"/>
		<h3 class="portfolio-title">Design<br/>Lessons Learnt</h3>
		<p class="portfolio-description">
		Find out more about some of the lessons Rich learnt from the previous website for <strong>The
		Vinyl Vault Show</strong>.
		</p>
		<p class="portfolio-description">
			<a href="blog/lessons-learnt-from-previous-vv-design">Read More</a>
		</p>
		<p class="portfolio-description">
			First Publish Date: 9 Feb 2022<br/>
			Last Updated: 13 Feb 2022

		</p>
		<code class="portfolio-tags">
		Tags:
		Design
		Mistakes
		</code>
	</div>

	<div class="portfolio-item">
		<img style="width:100%;border:1px solid black;" src="/static/rcw.jpg" alt="Website Design Is Under Cover"/>
		<h3 class="portfolio-title">DevLog:<br/>RichCodesWeb</h3>
		<p class="portfolio-description">
			Find out more about how this project was developed, and follow Rich's thought and
			development process.
		</p>
		<p class="portfolio-description">
			<a href="blog/devlog-richcodesweb">Read More</a>
		</p>
		<p class="portfolio-description">
			First Publish Date: 9 Feb 2022<br/>
			Last Updated: 13 Feb 2022

		</p>
		<code class="portfolio-tags">
		Tags:
		DevLog
		SvelteKit
		TailWind CSS
		</code>
	</div>
</div>
</div>
