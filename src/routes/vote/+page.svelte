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

<h2>2026 Endorsed Candidates</h2>

<div id="races-2026">
	<ul class="races">
		<li>
			<h3>Statewide Offices</h3>
			<ul class="candidates">
				<li>
					<div class="candidate">
						<div class="picture">
							<img src="/images/candidates/2026/jshapiro.jpg" alt="Josh Shapiro" />
						</div>
						<div class="name">Josh Shapiro</div>
					</div>
					<div class="race">Governor</div>
				</li>
				<li>
					<div class="candidate">
						<div class="picture">
							<img src="/images/candidates/2026/adavis.jpg" alt="Austin Davis" />
						</div>
						<div class="name">Austin Davis</div>
					</div>
					<div class="race">Lt. Governor</div>
				</li>
			</ul>
		</li>
		<li>
			<h3>Federal Offices</h3>
			<ul class="candidates">
				<li>
					<div class="candidate">
						<div class="picture">
							<img src="/images/candidates/2026/mdean.jpeg" alt="Madeleine Dean" />
						</div>
						<div class="name">Madeleine Dean</div>
					</div>
					<div class="race">U.S. House of Representatives (PA-04)</div>
				</li>
			</ul>
		</li>
		<li>
			<h3>State Legislature</h3>
			<ul class="candidates">
				<li>
					<div class="candidate">
						<div class="picture">
							<img src="/images/candidates/2026/ahaywood.jpg" alt="Art Haywood" />
						</div>
						<div class="name">Art Haywood</div>
					</div>
					<div class="race">State Senate (District 4)</div>
				</li>
				<li>
					<div class="candidate">
						<div class="picture">
							<img src="/images/candidates/2026/nnelson.jpg" alt="Napoleon Nelson" />
						</div>
						<div class="name">Napoleon Nelson</div>
					</div>
					<div class="race">State House of Representatives (District 154)</div>
				</li>
			</ul>
		</li>
		<li>
			<h3>Democratic State Committee (Senate District 4)</h3>
			<ul class="candidates">
				<li>
					<div class="candidate">
						<div class="name">Ayanna Laney-Martin</div>
					</div>
				</li>
				<li>
					<div class="candidate">
						<div class="name">Sandra L. Jenkins</div>
					</div>
				</li>
				<li>
					<div class="candidate">
						<div class="name">Dr. Craig Browne</div>
					</div>
				</li>
				<li>
					<div class="candidate">
						<div class="name">P. Darby Doyle</div>
					</div>
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

	ul.candidates {
		list-style: none;
		display: flex;
		flex-wrap: wrap;
		justify-content: center;
		padding: 5px;
		margin: 0px;
	}

	ul.candidates li {
		width: 320px;
		padding: 0px 10px;
		margin-top: 20px;
	}

	div.candidate {
		text-align: center;
		font-weight: bold;
		padding-bottom: 10px;
	}

	div.candidate div.name {
		font-size: 1.2em;
		white-space: nowrap;
	}

	div.race {
		text-align: center;
		background-color: #eee;
		font-weight: bold;
	}

	div.picture {
		margin: auto;
		width: 300px;
		height: 300px;
		overflow: hidden;
	}

	div.picture img {
		width: 100%;
		height: 100%;
		object-fit: cover;
		object-position: center 20%;
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
