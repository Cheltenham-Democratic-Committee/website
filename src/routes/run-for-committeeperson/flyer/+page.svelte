<svelte:head>
	<title>Run for Committee Person - Cheltenham Democratic Committee</title>
	<meta
		property="og:title"
		content="Run for Committee Person - Cheltenham Democratic Committee"
	/>
	<meta
		name="description"
		content="Be your block's voice in the Democratic Party. Run for Committee Person in Cheltenham in 2026."
	/>
</svelte:head>

<h1>Run for Committee Person in 2026</h1>

<p class="tagline">Be your block's voice in the Democratic Party.</p>

<p>
	Committee people are the grassroots of the Democratic Party — neighbors who connect voters to
	candidates, vote on endorsements, and help Democrats win. Every precinct in Cheltenham can elect
	<strong>two</strong>, and right now several seats are open. Yours could be one of them.
</p>

<h3>What you'd do <span class="time">(4–10 hours / month)</span></h3>
<ul>
	<li>Get to know the Democrats on your block</li>
	<li>Vote on candidate endorsements</li>
	<li>Help with voter registration, canvassing, and Get Out The Vote</li>
	<li>Attend monthly committee meetings</li>
</ul>

<h3>Who can run</h3>
<ul>
	<li>Registered Democrats who live in the precinct</li>
	<li>Collect ~10 signatures from Democratic neighbors on a nominating petition</li>
</ul>

<h3>2026 timeline</h3>
<div class="timeline">
	<div class="timeline-item">
		<div class="timeline-date">Feb 17</div>
		<div class="timeline-label">Filing opens</div>
	</div>
	<div class="timeline-item">
		<div class="timeline-date">Mar 10</div>
		<div class="timeline-label">Filing deadline</div>
	</div>
	<div class="timeline-item">
		<div class="timeline-date">May 19</div>
		<div class="timeline-label">Primary election</div>
	</div>
</div>
<p class="term-note"><em>Committee people serve a 4-year term.</em></p>

<h3>Curious? Ready?</h3>
<p class="cta">
	Email <a href="mailto:chairs@cheltdems.com">chairs@cheltdems.com</a> or learn more at
	<a href="/run-for-committeeperson">cheltdems.com/run-for-committeeperson</a>.
</p>

<style>
	.tagline {
		font-size: 1.2em;
		font-style: italic;
		color: #103578;
		text-align: center;
		margin-top: 0;
	}

	.time {
		font-weight: normal;
		font-size: 0.85em;
	}

	.timeline {
		display: flex;
		justify-content: space-between;
		align-items: flex-start;
		margin: 30px 0 10px;
		position: relative;
	}

	.timeline::before {
		content: '';
		position: absolute;
		top: 20px;
		left: 10%;
		right: 10%;
		height: 3px;
		background-color: #103578;
	}

	.timeline-item {
		text-align: center;
		flex: 1;
		position: relative;
	}

	.timeline-item::before {
		content: '';
		width: 16px;
		height: 16px;
		background-color: #103578;
		border-radius: 50%;
		display: block;
		margin: 12px auto 10px;
	}

	.timeline-date {
		font-size: 1.3em;
		font-weight: bold;
		color: #103578;
	}

	.timeline-label {
		font-size: 0.95em;
		color: #555;
	}

	.term-note {
		text-align: center;
		color: #555;
		margin-top: 0;
	}

	.cta {
		text-align: center;
		font-size: 1.1em;
	}
</style>
