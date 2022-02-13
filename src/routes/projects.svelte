<script context="module">
	import { browser, dev } from '$app/env';

	export const hydrate = dev;

	export const router = browser;

	export const prerender = true;
</script>

<svelte:head>
	<title>Rich's Projects & Portfolio | RichCodesWeb</title>
</svelte:head>

<div class="content">
	<h1>Rich's Projects & Portfolio</h1>

	<p class="portfolio-description">
		This is a small selection of Rich's past and current projects, in total Rich has worked on well over 100
		websites. For more information, please <a href="mailto:rich@richcodesweb.dev">email me</a>.
	</p>

	<div class="portfolio">
	    <div class="portfolio-item">
        <img style="width:100%;border:1px solid black;" src="/static/curtains.jpg" alt="Website Design Is Under Cover"/>
        <h3 class="portfolio-title">The Vinyl Vault Show (2022)</h3>
        <p class="portfolio-description">
        This will be Rich's <strong>Next</strong> personal project.
        Once completed, the library will replace the existing website.
        </p>
        <p class="portfolio-description">
        The design is currently under cover, but will be revealed soon! It's safe to say,
        that the default design is a significant departure from the current site.
        There will also be an alternative design available on a seperate sub-domain.
        </p>
        <p class="portfolio-description">
        GitHub: Coming Soon
        </p>
        <p class="portfolio-year">
        Year: SOON
        </p>
        <code class="portfolio-tags">
        Stack:
        React (Main Design)
        Nuxt3 (Alt. Design)
        TypeScript
        TailWind CSS
        </code>
	    </div>

        <div class="portfolio-item">
        <img style="width:100%;border:1px solid black;" src="/static/discogslib.jpg" alt="NPM and Node Logos"/>
        <h3 class="portfolio-title">TS Discogs Library</h3>
        <p class="portfolio-description">
        This is Rich's <strong>current</strong> project.
        Once completed, the library will feature multiple add-on modules.
        </p>
        <p class="portfolio-description">
        As a user of Discogs, Rich has used many libraries previously when developing
        previous versions of <strong>The Vinyl Vault Show</strong> website.  The existing solution for Node
        has been left derelict by its author, although Rich considered forking and continuing
        the development, he decided a fresh start would be best.
        </p>
        <p class="portfolio-description">
        The packages for this project are being uploaded to NPM for distribution<br/>
        NPM: <a href="https://github.com/VinylVault/" target="_blank">View On NPM</a>
        <p class="portfolio-description">
        GitHub: <a href="https://github.com/VinylVault/" target="_blank">Follow My Progress</a>
        </p>

        <p class="portfolio-year">
                Year: SOON
        </p>
        <code class="portfolio-tags">
        Stack:
        Node
        TypeScript
        Prisma
        Postgres
        Custom API
        </code>
	    </div>

	    <div class="portfolio-item">
        <img style="width:100%;border:1px solid black;" src="/static/rcw.jpg" alt="Screenshot of RichCodesWeb Website"/>
        <h3 class="portfolio-title">RichCodesWeb</h3>
        <p class="portfolio-description">
        This is Rich's <strong>Latest</strong> project.
        </p>
        <p class="portfolio-description">
        This is the project that created this website.  Rich decided on SvelteKit to create this website
        as an introduction to his JavaScript & TypeScript development journey.
        </p>
        <p class="portfolio-description">
        GitHub: <a href="https://github.com/VinylVault/" target="_blank">Star On GitHub</a>
        </p>
        <p class="portfolio-year">
        Devlog: <a href="blog/devlog-richcodesweb">Read The Blog Post</a>
        </p>
        <p class="portfolio-year">
        Year: 2022
        </p>
        <code class="portfolio-tags">
        Stack:
        Node
        TypeScript
        SvelteKit
        TailWind CSS
        </code>
        </div>

	    <div class="portfolio-item">
        <img style="width:100%;border:1px solid black;" src="/static/tvv21.jpg" alt="Screenshot of The Vinyl Vault Show (2021) Website"/>
        <h3 class="portfolio-title">The Vinyl Vault Show (Current Version)</h3>
        <p class="portfolio-description">
        This is the <strong>Current</strong> version of <a href="https://www.thevinylvaultshow.co.uk" target="_blank">The Vinyl Vault Show Website</a>.
        </p>
        <p class="portfolio-description">
        There are multiple parts to this website.  In the background there is a <strong>Python</strong> import
        script which talks to the Discogs API, using the <a href="https://github.com/joalla/discogs_client" target="_blank">Joalla</a> Python Discogs library
        and saves the information to a local database along with downloading the relevant artwork.
        </p>
        <p class="portfolio-description">
        Rich took, and still takes an active part in the Joalla forums, helping other users with issues, and
        making suggestions for improvements to the library.
        </p>
        <p class="portfolio-description">
        The design of the website was created by Rich, to complement the <a href="https://www.twitch.tv/vinylvault" target="_blank">Twitch</a> Live Stream package.<br/>
        The Twitch Streams, will be updated with the new website deisgn.
        </p>
        <p class="portfolio-description">
        GitHub: <a href="https://github.com/VinylVault/" target="_blank">Star On GitHub</a>
        </p>
        <p class="portfolio-year">
        Years Active: 2020 - 2022
        </p>
        <code class="portfolio-tags">
        Stack:
        Python
        Django
        Bootstrap CSS
        Postgres Database
        </code>
        </div>

	    <div class="portfolio-item">
        <img style="width:100%;border:1px solid black;" src="/static/silentchild.jpg" alt="Screenshot of The Silent Child Website"/>
        <h3 class="portfolio-title">The Silent Child</h3>
        <p class="portfolio-description">
        This is the website for the OSCAR&reg; Winning Short Film <strong>The Silent Child</strong>.
        </p>
        <p class="portfolio-description">
        Rich was asked to do this website as a project for his previous company <strong>Optik Web Creative</strong> by
        Rachel & Chris Overton (Writer / Lead Actress and Director).  Rich became a small financial backer of the production
        and A/V provider for local events around the Stoke on Trent area.
        </p>
        <p class="portfolio-description">
        The website was part of the submission to the OSCAR&reg; submission and featured information about cast and crew
        along with dates of events relating to showings of the film.  The site was very image heavy, but with optimisations,
        still loaded with A+ ratings from GTMetrix.
        </p>
        <p class="portfolio-description">
        The website was taken down at the end of the film tour.
        </p>
        <p class="portfolio-description">
        Fun Fact: Rich has held an OSCAR&reg; Statuette.
        </p>
        <p class="portfolio-year">
        Years Active: 2018 - 2020
        </p>
        <code class="portfolio-tags">
        Stack:
        GRAV
        FlatFile Database
        Bootstrap CSS
        </code>
        </div>

	    <div class="portfolio-item">
        <img style="width:100%;border:1px solid black;" src="/static/owc.jpg" alt="testimage"/>
        <h3 class="portfolio-title">Optik Web Creative<br/>(Company)</h3>
        <p class="portfolio-description">
        This was Rich's <strong>Web Development Company</strong>.
        </p>
        <p class="portfolio-description">
        Whilst Rich was running and devloping for <strong>Optik Web Creative</strong>, Rich worked on over
        100 Websites.
        </p>
        <p class="portfolio-description">
        From working with <strong>Agencies</strong> to <strong>Private Clients</strong> Rich both
        developed full website from the design stage, and converted designs sent into reality on the web.
        </p>
        <p class="portfolio-description">
        From simple brochure websites to more complex sites and complete custom coded solutions Rich worked
        on them all.  Rich also coded additional extensions for existing <strong>Joomla</strong> and <strong>
        Wordpress</strong> components, both through liasing with the existing developers and solo work.
        </p>
        <p class="portfolio-description">
        Rich worked on websites across many industries, including: Real Estate, After School Provision, Finance,
        Music, Community Centers, Radio Stations and many more.
        <p class="portfolio-year">
        Years Active: 2016 - 2020
        </p>
        <code class="portfolio-tags">
        Stack:
        PHP
        Joomla
        WordPress
        MySQL Database
        Postgres
        Custom APIs
        Bootstrap
        Custom CSS
        </code>
        </div>


	</div>


</div>

<style>
	.content {
		width: 100%;
		max-width: var(--column-width);
		margin: var(--column-margin-top) auto 0 auto;
	}


</style>
