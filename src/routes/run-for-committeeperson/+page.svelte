<svelte:head>
	<title>Run for Committee Person - Cheltenham Democratic Committee</title>
	<meta property="og:title" content="Run for Committee Person - Cheltenham Democratic Committee" />
</svelte:head>

<h1>Run for Committee Person</h1>

<p>
	Committee people are the grassroots foundation of the Democratic Party. Each voting precinct in
	Cheltenham Township can elect up to two Democratic committee people who serve four-year terms. As
	a committee person, you are the face of the party in your neighborhood—connecting voters with
	candidates, shaping endorsements, and getting Democrats elected.
</p>

<h3>Responsibilities</h3>
<ul>
	<li>Get to know voters in your precinct and share information about Democratic candidates</li>
	<li>Vote on endorsements at CDC, Area, and County Committee meetings</li>
	<li>Help with voter registration and Get Out The Vote (GOTV) efforts</li>
	<li>Participate in phone banking, canvassing, and election day activities</li>
	<li>Attend monthly CDC meetings</li>
</ul>

<h2>How to Run in 2026</h2>

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

<h3>Requirements</h3>
<ul>
	<li>Be a registered Democrat</li>
	<li>Reside in the precinct you want to represent</li>
	<li>
		Gather signatures on a nominating petition (typically 10 signatures from registered Democrats in
		your precinct)
	</li>
	<li>File your petition with the Montgomery County Board of Elections during the filing period</li>
</ul>

<h3>Steps to File</h3>
<ol>
	<li>
		Determine your ward and precinct using the <a
			href="https://slifty.github.io/cheltenham-ward-map/"
			target="_blank">Cheltenham Ward Map</a
		>
	</li>
	<li>
		Obtain nominating petition forms from the <a
			href="https://www.montgomerycountypa.gov/753/Voter-Services"
			target="_blank">Montgomery County Board of Elections</a
		>
	</li>
	<li>Collect the required signatures from registered Democrats in your precinct</li>
	<li>
		File your completed petition at the Montgomery County Board of Elections between February 17 -
		March 10, 2026
	</li>
</ol>

<h2>Contact Information</h2>
<div class="contact-info">
	<h3>Montgomery County Board of Elections</h3>
	<ul>
		<li><strong>Address:</strong> One Montgomery Plaza, Suite 602, Norristown, PA 19404</li>
		<li><strong>Phone:</strong> (610) 278-3280</li>
		<li>
			<strong>Website:</strong>
			<a href="https://www.montgomerycountypa.gov/753/Voter-Services" target="_blank"
				>Montgomery County Voter Services</a
			>
		</li>
	</ul>

	<h3>Cheltenham Democratic Committee</h3>
	<p>
		Have questions? Contact us at <a href="mailto:chairs@cheltdems.com">chairs@cheltdems.com</a>
	</p>
</div>

<style>
	.timeline {
		display: flex;
		justify-content: space-between;
		align-items: flex-start;
		margin: 30px 0;
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

	.contact-info {
		background-color: #eee;
		padding: 15px 20px;
		margin: 20px 0;
	}

	.contact-info h3 {
		background-color: transparent;
		text-align: left;
		padding: 0;
	}

	ol li {
		margin-bottom: 10px;
	}
</style>
