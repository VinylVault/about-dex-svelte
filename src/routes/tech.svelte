<script context="module">
	import { browser, dev } from '$app/env';

	export const hydrate = dev;

	export const router = browser;

	export const prerender = true;
</script>

<svelte:head>
	<title>Rich's Tech Stack | RichCodesWeb</title>
</svelte:head>

<div class="content">
	<h1>Rich's Tech Stack</h1>

    <p>
	<code>
	Home:<br/>
	Windows 10 PC - Multiple Monitors<br/>
	SmartPhones & Tables:
	--> Multiple Brands
	--> Multiple Models
	--> Operating Systems<br/>
	JetBrains IDE Suite<br/>
	Visual Studio Code<br/>
	ProxMox HomeLab:
	--> Ubuntu Server - Docker (Python, PHP, Node, Apache)
	--> Ubuntu Server - Nextcloud<br/>
	Multiple NAS
	</code>
	</p>

	<p>
	<code>
	Servers:<br/>
	Docker Environment (Multiple Containers):<br/>
	Alpine Linux<br/>
	Ubuntu<br/>
	Python:
	-->Development Test Environments (One Per Site)
	-->Production Test Environments (One Per Site)
	-->Live Environments (One Per Site)<br/>
	Node:
	-->Development Test Environments (One Per Site)
	-->Production Test Environments (One Per Site)
	-->Live Environments (One Per Site)<br/>
	Postgres (x1)<br/>
	MySQL (x1)<br/>
	LetsEncrypt: (x1)
	-->Multiple Domains
	-->Auto-Renew Configured<br/>
	NginX Proxy (x1)

	WordPress

	SelfHosted GitLab</code></p>

</div>

<style>
	.content {
		width: 100%;
		max-width: var(--column-width);
		margin: var(--column-margin-top) auto 0 auto;
	}
</style>
