<script context="module">
  import { browser, dev } from '$app/env';
  import './blog.css';
  export const hydrate = dev;

  export const router = browser;

  export const prerender = true;
</script>

<svelte:head>
  <title>Devlog: RichCodesWeb | RichCodesWeb</title>
</svelte:head>

<div class="content">
  <div class="blogheader">
    <div class="blogImage">
      <img style="width:100%;border:1px solid black;" src="/static/rcw.jpg" alt="RichCodesWeb ScreenShot"/>
    </div>
    <div class="blogMeta">
      <h1>Devlog: RichCodesWeb</h1>
      <h3>Written By: Rich</h3>
      <h4>Publish Date: 10 Feb 2022<br/>
          Last Update: 13 Feb 2022</h4>
      <code>Devlog</code> | <code>SvelteKit</code> | <code>Tailwind CSS</code>
    </div>
  </div>
  <div class="blogContent" id="080222">
    <p>
      Welcome to the first blog on RichCodesWeb!
    </p>
    <p>
      <strong>8 Feb 2022</strong>
    </p>
    <p>Jump To Update : <a href="#100222">10 Feb 2022</a> | <a href="#130222">13 Feb 2022</a> </p>
    <p>
      I started this thinking about this project a couple of weeks ago, wanting a simple CV and Portfolio
      site that I could point potential employers and customers too.  So I started by evaluating my online
      presence.  On Twitch, I used the moniker DexVinyl, which although neutral was at least in my mind tied
      to my Radio persona, and not really a name I wanted to continue using for personal / web development
      streaming and I was already using
      <a href="https:/twitter.com/RichCodesWeb" target="_blank">@RichCodesWeb</a> on Twitter, so I changed my
      Twitch to <a href="https://www.twitch.tv/RichCodesWeb" target="_blank">RichCodesWeb</a> and bought the
      <a href="https://www.richcodesweb.dev">.dev</a>, <a href="https://www.richcodesweb.me">.me</a> and
      <a href="https://www.richcodesweb.co.uk">.co.uk</a> web domains (hint: they all point here).
    </p>
    <p>
      The choice to use <strong>SvelteKit</strong> was a relatively easy one, I had already whilst looking at
      doing <strong>The Vinyl Vault Show</strong> website made the decision that I was going to use
      <strong>React</strong> and <strong>Vue3</strong>/<strong>Nuxt3</strong> for the two designs that I am
      going to make, and I wanted to continue using <strong>TypeScript</strong> based code.
      <strong>SvelteKit</strong> although being a new-ish player in this arena has grabbed plenty of
      market share, and has a lot of traction in the community.
    </p>
    <p>
      So, I fired up <strong>JetBrains WebStorm</strong> entered the <strong>Terminal</strong> and followed the guide at <a href="https://kit.svelte.dev" target="_blank">kit.svelte.dev</a>
      to install locally and see what was what. For CSS, I knew I wanted <strong>TailWind</strong> simply because
      I had done a little playing with it and wanted to learn more.
    </p>
  </div>
  <div class="blogContent" id="100222">
    <p>
      <strong>10 Feb 2022</strong>
    </p>
    <p>Jump To Update : <a href="#080222">8 Feb 2022</a> | <a href="#130222">13 Feb 2022</a></p>

    <p>
      First day of "Development Proper".
    </p>
    <p>
      For the design of this site, I wanted something super simple, DarkMode locked
      (Who wants <em>all</em> the lumens?) with a static menu. Due to the content and
      intent of the site, I designed it desktop first.  Design work done in <strong>GIMP</strong>
      (GNU Image Manipulation Program).
    </p>
    <p>
      Of course every site needs a logo of some sort, so I went to a couple of free online
      logo generator sites to see a few options and get ideas. As I expected, nothing really
      grabbed my attention, so I turned back to <strong>GIMP</strong>, and <strong>FontAwesome</strong>.
      That was good enough for a temporary logo.
    </p>
    <p>
      With the logo completed, I started out on the <strong>Svelte</strong> Layout file for the site,
      and the CSS using the <span style="font-family: 'Fira Code';">@apply</span> rule to keep the code
      clean from long lines of <strong>Tailwind CSS</strong> classes.
    </p>
    <p>
      Once the layout was completed, and I liked the colour scheme I started to create the pages.
      Starting with the <span style="font-family: 'Fira Code';">About</span> Page, which will always
      serve as the homepage. Once I'd planned that out and written the <strong>About</strong> and
      <strong>Core Competencies</strong> sections, I moved to the <span style="font-family: 'Fira Code';">
      Tech Stack</span> page, finally I started planning out and getting screenshots for the
      <span style="font-family: 'Fira Code';">Projects</span> page.
    </p>
  </div>
  <div class="blogContent" id="130222">
    <p>
      <strong>13 Feb 2022</strong>
    </p>
    <p>Jump To Update : <a href="#080222">8 Feb 2022</a> | <a href="#100222">10 Feb 2022</a></p>

    <p>
      First day of "Development Proper".
    </p>

  </div>

</div>

<style>
  code {
    display: initial !important;
    padding: 0.5rem;margin-bottom: 2rem;
    border-bottom-width: 0px;
    --tw-shadow-color: rgb(107 114 128 / 0.5);
    --tw-shadow: var(--tw-shadow-colored);
    font-variant: small-caps;
  }

  @supports (font-variation-settings: normal) {
    code {
      display: initial !important;
      padding: 0.5rem;margin-bottom: 2rem;
      border-bottom-width: 0px;
      --tw-shadow-color: rgb(107 114 128 / 0.5);
      --tw-shadow: var(--tw-shadow-colored);
      font-variant: small-caps;
    }
  }

</style>