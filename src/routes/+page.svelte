<script>
	import Meetings from '$lib/Meetings.svelte';
</script>

<svelte:head>
	<title>The Cheltenham Democratic Committee</title>
	<meta property="og:title" content="The Cheltenham Democratic Committee" />
	<meta property="og:url" content="https://cheltenhamdemocrats.org" />
</svelte:head>

<div id="banner">
	<img src="/images/banner.png" alt="" />
</div>

<div id="actions">
	<div>
		<a class="ml-onclick-form button" href="/" onClick="ml('show', 'sdV778', true)"
			>Join our mailing list</a
		>
	</div>
	<div>
		<a class="button" href="/donate">Donate</a>
	</div>
</div>
<div class="banner">
	2026 is a committee person election year!
	<a href="/run-for-committeeperson">Learn how to run</a>.
</div>

<h2>Meetings</h2>
<Meetings />

<style>
	#actions {
		display: flex;
		flex-wrap: wrap;
		justify-content: space-evenly;
	}
	#actions a {
		width: 300px;
		margin: 5px;
	}

	#banner {
		width: 100%;
		margin-bottom: 20px;
	}
	#banner img {
		width: 100%;
	}
	.banner {
		margin: 30px;
		padding: 20px;
		text-align: center;
		font-size: 1.4em;
		background-color: #f9d362;
	}
</style>
