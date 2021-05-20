<script>
  import PageTitle   from "/src/components/pageTitle.svelte";
</script>

<body>

<!--Main Title-->
<PageTitle>
  <span slot="title">
		Imagine a place...
	</span>
	<span slot="subtitle">
		...where you can research features with your fellow Discord users, experimenting and all. A place where no feature is left behind.
	</span>
</PageTitle>

<!--Join\ Title-->
  <div id="joinTitle" class="joinTitle" >
    <h2>Join today!</h2>
  </div>

<a class="joinButton" href="//discord.gg/d6yDFXNs7z" target=_blank>Discord Server Invite</a>
<a class="joinButton" href="//github.com/discord-labs" target=_blank>GitHub Organisation</a>

<p>Discord Labs is not affiliated with Discord in any way.</p>

</body>

<style>
	.joinButton {
		background-color: #5BC0BE;
		padding: 10px;
		color: black;
		border-radius: 32px;
	}

	p {
		color: lightgray;
		margin-top: 1.5rem;
	}
</style>