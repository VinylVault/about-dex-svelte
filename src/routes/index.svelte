<script context="module" lang="ts">
	export const prerender = true;
</script>

<script lang="ts">
	import Counter from '$lib/Counter.svelte';
</script>

<svelte:head>
	<title>Home | RichCodesWeb</title>
</svelte:head>


<section>
	<h1>
		<div class="welcome">
            <img src="svelte-welcome.webp" alt="Welcome" />
		</div>
	</h1>
	<h2 style="margin:0; text-align:center;">
		... to my container on the Internet!
	</h2>

	<h3>
		About Rich!
	</h3>
	<p>
		I am a self-motivated, highly experienced IT Professional.
		<br/>
		I have been a full-stack web developer for approximately 15 years and before that I worked
		primarily in the Support & Helpdesk side of IT.
		<br/>
		I have recently got into <a href="https://www.twitch.tv/RichCodesWeb" target="_blank">Twitch Streaming</a> my
		Web and Software Development.
	</p>
	<p>
		I have a keen desire to learn, which is why I teach myself (with the help of YouTube videos,
		and Twitch Streams) at least one new language or framework each and every year.
	</p>
	<p>
		Outside of code writing, I am a self confessed Vinyl Addict, and amateur Radio Presenter on a number
		of Internet Radio Stations, but this website is not for that!
		<a href="https://www.thevinylvaultshow.co.uk" target="_blank"> You can find out more about that here</a>
	</p>

	<h3>
		Rich's CV!
	</h3>
	
	<p>
		I am fully aware this is a public website, so the details on here, you may find lacking in personal details.
		  If you would like to find out more, please <a href="mailto:rich@richcodesweb.dev">email me</a>.
	</p>

	<h4>
		Core Competencies
	</h4>
	<p>
		These Competencies are not listed in any order of expertise, I feel comfortable enough to list
		them here, as a competency that I would be able to work well in, at a professional level.<br/>
	</p>
	<p>
	<code>
	Languages & Frameworks:
	--> PHP
	--> WordPress
	--> Joomla
	--> Python
	--> Django
	--> HTML5
	--> CSS3
	--> Bootstrap
	</code>
	</p>
    <p>
	<code>
	Operating Systems:
	--> Linux - Debian / CentOS / Ubuntu
	--> Microsoft Windows
	--> MacOS
	--> iPadOS
	--> iOS
	--> Android
	</code>
	</p>
    <p>
	<code>
	Other:
	--> Docker
	--> Microsoft Visual Studio Code
	--> Adobe Creative Suite
	--> Git / GitHub / GitLab
	--> API Data Access and Manipulation
	--> GDPR Compliance
	</code>
	</p>

	<h4>
		Ongoing Learning
	</h4>
	<p>
		These Competencies are not listed in any order of expertise, I feel comfortable enough to list
		them here, as a competency that I would be able to work in, just not necessarily at a professional level.<br/>
	</p>
    <p>
    <code>
	Languages & Frameworks:
	--> TypeScript
	--> Vue
	--> React
	--> Svelte
	--> TailWind CSS
	--> Ruby on Rails
	</code>
    </p>
    <p>
    <code>
    Other:
    --> Amazon Web Services
    </code>
    </p>
    <p>
        These Competencies are not listed in any order, I do not, yet feel comfortable enough to list
        them here, as a competency that I would be able to work in, but they should soon be moving to the above section.<br/>
    </p>
    <p>
    <code>
    Other:
    --> Figma
    </code>
    </p>
	<h4>
		Employment History
	</h4>

	<p>
		These Competencies are not listed in any order of expertise, I feel comfortable enough to list
		them here, as a competency that I would be able to work in, just not at a professional level.
	</p>

</section>

<style>
	header {
	}

	section {
		display: flex;
		flex-direction: column;
		flex: 1;
	}

	.welcome {
		width: 100%;
	}

	.welcome img {
		width: 100%;
		height: 100%;
		display: block;
	}
</style>
