<svelte:head>

    <link href="/main.css" rel="stylesheet" />
	<title>Discord Labs - Site</title>
    <link rel="icon" href="/favicon.ico" />

    <meta http-equiv="Cache-control" content="no-cache">

    <meta property="og:title" content="Discord Labs - Site" />
    <meta property="og:type" content="website" />
    <meta property="og:url" content="https://discord-labs.vercel.app" />
    <meta property="og:image" content="https://discord-labs.vercel.app/assets/siteLogo.png" />
    <meta property="og:description" content="Welcome to the offical site of Discord Labs!" />
    <meta name="theme-color" content="#6FFFE9">

</svelte:head>

<script>
    import GitHubLogo  from "/src/components/githubLogo.svelte"
    import DiscordLogo from "/src/components/discordLogo.svelte"
    import SiteLogo    from "/src/components/siteLogo.svelte"
    import Banner      from "/src/components/banner.svelte"
</script>

<nav>
    <div id="navbar" class="navbar" >
        <div class="nav-top">
            <SiteLogo width="20px" height="20px"/>
            <strong>Discord Labs</strong>
        </div>
        <div class="nav-bottom">
            <a class="navButton" href="/">Home</a>
            <a class="navButton" href="/faq">FAQ</a>
            <a class="navButton" href="/credits">Site credits</a>
            <!-- <div class=buttonContainer>
                <GitHubLogo repo="" />
            </div> -->
        </div>
    </div>
</nav>

<main>
    <div class="container">
    <slot/>
    </div>
</main>

<style>
    main {
        align-self: center;
    }

    .navbar {
        display: flex;
        flex-direction: column;
        border-radius: 16px;
    }

    .nav-top {
        text-align: center;
        background-color: #1c2541;
        color: #fff;
        padding: 10px;
        border-radius: 16px;
        margin-bottom: 3px;
    }

    .nav-bottom {
        text-align: center;
        background-color: #1c2541;
        color: #fff;
        padding: 10px;
        border-radius: 16px;
    }

    .navButton {
        padding: 5px;
        border-radius: 8px;
        background-color: #3A506B;
        color: #fff;
        transition: color ease .2s;
        margin-right: 3px;
    }

    .navButton:hover {
        color: rgb(204, 204, 204);
    }

    /* .buttonContainer {
        margin-left: 5px;
        float: right;
    } */
</style>