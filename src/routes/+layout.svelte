<svelte:head>
	<link rel="stylesheet" href="/main.css" />
	<meta name="description" content="" />
	<meta property="og:type" content="website" />
	<meta property="og:image" content="" />
	<meta property="og:description" content="" />
	<script>
		(function (w, d, e, u, f, l, n) {
			(w[f] =
				w[f] ||
				function () {
					(w[f].q = w[f].q || []).push(arguments);
				}),
				(l = d.createElement(e)),
				(l.async = 1),
				(l.src = u),
				(n = d.getElementsByTagName(e)[0]),
				n.parentNode.insertBefore(l, n);
		})(window, document, 'script', 'https://assets.mailerlite.com/js/universal.js', 'ml');
		ml('account', '468218');
	</script>
</svelte:head>

<div id="header">
	<div id="logo">
		<a href="/"><img src="/images/logo.png" alt="" /></a>
	</div>
	<nav>
		<ul>
			<li><a href="/about">Who We Are</a></li>
			<li><a href="/get-involved">Get Involved</a></li>
			<li><a href="/vote">Vote</a></li>
			<li><a href="/donate">Donate</a></li>
		</ul>
	</nav>
</div>

<div id="main">
	<div id="content">
		<slot />
	</div>
</div>

<div id="footer">
	<div class="social">
		Follow us on <a href="https://www.facebook.com/cheltdems">Facebook</a>
	</div>
	<div>
		<em>This site is Open Source.</em> Want to make an improvement?
		<a href="https://github.com/Cheltenham-Democratic-Committee/website/">Open a PR</a>.
	</div>
</div>

<style>
	#header {
		text-align: center;
	}

	#logo img {
		max-width: 250px;
		margin: 10px;
	}

	nav {
		max-width: 800px;
		margin: auto;
		font-weight: normal;
	}

	nav ul {
		display: flex;
		flex: 1 1 0px;
		flex-wrap: wrap;
		justify-content: space-evenly;
		margin: 5px;
	}

	nav li {
		display: block;
		width: 150px;
		list-style: none;
	}

	nav li a {
		text-decoration: none;
	}

	#main {
		border-top: 5px solid #103578;
		border-bottom: 5px solid #103578;
		padding: 20px;
	}
	#content {
		max-width: 800px;
		margin: auto;
	}
	#footer {
		text-align: center;
		margin-top: 40px;
		font-size: 0.8em;
	}
</style>
