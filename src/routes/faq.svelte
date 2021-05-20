<script>
    import PageTitle  from "/src/components/pageTitle.svelte"
</script>

<body>
    <PageTitle>
        <span slot="title">
              FAQ
          </span>
          <span slot="subtitle">
            Want to know what Discord Labs is? Or maybe what we do? Look no further than the FAQ!
          </span>
    </PageTitle>
    
    <div class="faqItem">
        <h2>What is Discord Labs?</h2>
        Discord Labs is a server dedicated to finding and testing out new or experimental features in Discord. These can be features in the client, features in the API, and other general discoveries!
    </div>

    <div class="faqItem">
        <h2>How do I report something I've found?</h2>
        Simply send what you've found in the Discord server's #discoveries channel, optionally following the template. If it's extra cool, we might highlight it in the Discord server's #notable-discoveries channel, and everyone will revel in your presence. (Okay, maybe not...)
    </div>

    <div class="faqItem">
        <h2>How do I join?</h2>
        Well, it's simple! The invite link is https://discord.gg/d6yDFXNs7z, but you could just click the button on our <a href='/'>main page</a>!
    </div>

    <div class="faqItem">
        <h2>Wait... Are you copying Discord Datamining?</h2>
        Well... Kinda. However, we aim to take a much more general approach, not entirely focusing on comparing JavaScript between updates, moreso the physical benefits and downsides of features.
    </div>
</body>

<style>
    .faqItem {
        padding: 10px;
        border-radius: 16px;
        background-color: #1c2541;
        margin-bottom: 15px;
    }
</style>