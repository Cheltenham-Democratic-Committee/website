<svelte:head>
	<title>Vote - Cheltenham Democratic Committee</title>
	<meta property="og:title" content="Vote - Cheltenham Democratic Committee" />
</svelte:head>

<div class="election-dates">
	<div class="date-card">
		<h3>Primary Election</h3>
		<div class="date">May 19, 2026</div>
	</div>
	<div class="date-card">
		<h3>General Election</h3>
		<div class="date">November 3, 2026</div>
	</div>
</div>

<h2>2026 Races</h2>
<p>
	Endorsements for the 2026 elections have not yet been made. Below are the offices on the ballot.
</p>

<div id="races-2026">
	<ul class="races">
		<li>
			<h3>Statewide Offices</h3>
			<ul class="offices">
				<li>Governor</li>
				<li>State Treasurer</li>
			</ul>
		</li>
		<li>
			<h3>Federal Offices</h3>
			<ul class="offices">
				<li>U.S. House of Representatives (PA-04 District)</li>
			</ul>
		</li>
		<li>
			<h3>State Legislature</h3>
			<ul class="offices">
				<li>State Senate</li>
				<li>State House of Representatives</li>
			</ul>
		</li>
		<li>
			<h3>Democratic Committee</h3>
			<ul class="offices">
				<li>
					<a href="/run-for-committeeperson">Committee Person Elections</a> - Learn how to run!
				</li>
			</ul>
		</li>
	</ul>
</div>

<h2>Voter Resources</h2>
<ul>
	<li><a href="https://mcdems.org/votingcenter/">Montgomery County Democrats voting center</a></li>
	<li>
		<a href="https://www.vote.pa.gov/Pages/default.aspx">PA voting and election information</a>
	</li>
	<li>
		<a href="https://www.pavoterservices.pa.gov/Pages/VoterRegistrationApplication.aspx"
			>Register to vote</a
		>
	</li>
	<li>
		<a href="https://www.vote.pa.gov/Voting-in-PA/Pages/Mail-and-Absentee-Ballot.aspx"
			>Apply for a mail-in or absentee ballot</a
		>
	</li>
</ul>

<style>
	.election-dates {
		display: flex;
		flex-wrap: wrap;
		justify-content: space-around;
		gap: 20px;
		margin: 20px 0;
	}

	.date-card {
		background-color: #103578;
		color: white;
		padding: 20px 40px;
		text-align: center;
		min-width: 200px;
	}

	.date-card h3 {
		background-color: transparent;
		color: #f9d95c;
		margin-bottom: 10px;
	}

	.date-card .date {
		font-size: 1.4em;
		font-weight: bold;
	}

	ul.offices {
		list-style: disc;
		padding-left: 40px;
	}

	ul.offices li {
		text-align: left;
		padding: 5px 0;
	}

	ul.races {
		list-style: none;
		border: 4px solid #eee;
		padding: 0px;
		margin: 0px;
	}

	ul.races > li {
		margin-top: 20px;
	}
	ul.races > li:first-of-type {
		margin-top: 0px;
	}
	ul.races > li:first-of-type h3 {
		margin-top: 0px;
	}
</style>
