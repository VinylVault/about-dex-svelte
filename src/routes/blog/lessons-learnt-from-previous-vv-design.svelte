<script context="module">
    import { browser, dev } from '$app/env';
    import './blog.css';
    export const hydrate = dev;

    export const router = browser;

    export const prerender = true;
</script>

<svelte:head>
    <title>Design Lessons Learnt From Previous Vinyl Vault Show Website | RichCodesWeb</title>
</svelte:head>

<div class="content">
    <div class="blogheader">
        <div class="blogImage">
            <img style="width:100%;border:1px solid black;" src="/static/tvv21.jpg" alt="RichCodesWeb ScreenShot"/>
        </div>
        <div class="blogMeta">
            <h1>Design Lessons Learnt</h1>
            <h3>Written By: Rich</h3>
            <h4>Publish Date: 10 Feb 2022<br/>
                Last Update: 13 Feb 2022</h4>
            <code>Design</code> | <code>Mistakes</code>
        </div>
    </div>
    <div class="blogContent">
        <p>
            Mistakes were made with the design of the 2021/2022 version of <strong>The Vinyl Vault Show</strong>
            website.
        </p>
        <p>
            The design for <strong>The Vinyl Vault Show</strong> was created based on the design of the
            <a href="https://www.twitch.tv/VinylVault" target="_blank">Twitch</a> Stream, which although that design
            suited the stream, and Rich thought that having some consistency in the branding and look, in hindsight,
            this was a mistake.  Although the majority of the design works quite well, there are elements that should
            have never made it into production.  Rich, being Rich, liked them so they did.
        </p>
        <p>
            Reflecting on the design choices, Rich <strong>should</strong> have taken the stream design from a working,
            professional looking website, rather than taking the website design from a casual design for a twitch stream.
            This mistake <strong>will not</strong> be made again.
        </p>
        <p>
            Going forward, once I've mastered <strong>Figma</strong>, all Websites will be designed in
            <strong>Figma</strong>, and where needed, so will Stream Graphics.
        </p>
        <p>
            Once I've completed the RichCodesWeb site, and also the Discogs Library Tool (but not necessarily all the add-ons)
            I'll start with a concerted effort to learn and master <strong>Figma</strong>.
        </p>
        <p>
            You will be able to follow this learning process as well as all my coding adventures on
            <a href="https://www.twitch.tv/RichCodesWeb" target="_blank">My Twitch Channel</a> LIVE.
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