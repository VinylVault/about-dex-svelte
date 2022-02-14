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
		Here is a brief history of Rich's work life.
	</p>
	<div class="frame">
		<pre>
		Company -> Various<br/>
		<br/>
		Years -> 2018 to Present<br/>
		<br/>
		Job Title -> Ad-Hoc Beta Tester<br/>
		<br/>
		About -> Naturally, I can't go into details about the companies and products that I have been involved in Beta
		Testing, but in general terms, I have worked on: <br/>
		-> <strong>Operating Systems</strong> (Closed and Public Beta Programs),<br/>
		-> <strong>Games</strong> (Closed and Public Beta Programs),<br/>
		-> <strong>Numerous Open Source Projects</strong>
		</pre>
	</div>

	<div class="frame">
		<pre>
		Company -> Various<br/>
		<br/>
		Years -> 2019 to Present<br/>
		<br/>
		Job Title -> Various Roles<br/>
		<br/>
		About -> In 2019, A life changing series of personal circumstances paid a visit, which resulted in the need to close
		down Optik Web Creative, and for me to change the area in which I live.<br/>
		<br/>
		Despite this, after a period of time for me to re-adjust, I applied myself to learning and improving my web
		development skills, learning new technologies and languages (including Python) via online training courses.<br/>
		<br/>
		In recent weeks, I have started to develop my own Open Source TypeScript Library and suite of Add-Ons.<br/>
		<br/>
		I also turned my hand to employment outside of IT, proving to be adept at Just-In-Time Same Day deliveries via
		agencies for household names such as Amazon, and Wickes.
		</pre>
	</div>

	<div class="frame">
		<pre>
		Company -> Optik Web Creative<br/>
		<br/>
		Years -> 2016 to 2019<br/>
		<br/>
		Job Title -> Managing Director, and Chief Web Developer<br/>
		<br/>
		About -> Main point of customer contact, for sales enquiries and design work.<br/>
		<br/>
		Recruiting and Managing Staff<br/>
		<br/>
		Designing and Developing vibrant, engaging and unique websites for customers, both direct and via agencies,
		using a variety of technologies including WordPress, Joomla, Magento and Custom-built PHP websites.
		</pre>
	</div>

	<div class="frame">
		<pre>
		Company -> Various Agencies<br/>
		<br/>
		Years -> 2000 to 2016<br/>
		<br/>
		Job Title -> Computer Consultant, Helpdesk Engineer, Software Engineer<br/>
		<br/>
		About -> Being an IT contractor, I had to be able to hit the ground running very quickly on starting with a
		company.  <br/>
		<br/>
		Contracts would typically vary from 4-weeks to 6-months with occasional longer contracts upto 12-months.<br/>
		<br/>
		For a typical Helpdesk role, I would have to learn any specific systems, and policies quickly, without asking
		too many questions of the hiring manager or other colleagues.<br/>
		<br/>
		Computer Consultant roles, would naturally vary between Desktop and Server Hardware Rollouts, to servicing
		hardware either in the field or in the home base office.<br/>
		<br/>
		For me, though the most challenging and enjoyable roles were the Software Engineering, which although very
		similar to a Helpdesk role, the software and challenges were significantly different, as I would be
		specifically supporting in-house written software, and writing bug reports to send to the development team.
		</pre>
	</div>

</section>

<style>
	.frame{
		margin: 1em 0px;
		@apply bg-gray-500/10 block text-white border-b-4 rounded-sm border-orange-600 shadow-lg shadow-orange-600/50 p-4;
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
	
	pre {
		white-space: normal;
		text-align: justify;
		font-family: 'Fira Code';
	}
</style>
