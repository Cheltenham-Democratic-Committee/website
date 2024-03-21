<h1>Vote</h1>
<h2>Voter Resources</h2>
<ul>
	<li><a href="https://mcdems.org/votingcenter/">Montgomery County Democrats voting center</a>.</li>
	<li>
		<a href="https://www.vote.pa.gov/Pages/default.aspx">PA voting and election information</a>.
	</li>
	<li>
		<a href="https://www.pavoterservices.pa.gov/Pages/VoterRegistrationApplication.aspx"
			>Register to vote</a
		>.
	</li>
	<li>
		<a href="https://www.vote.pa.gov/Voting-in-PA/Pages/Mail-and-Absentee-Ballot.aspx"
			>Apply for a mail-in or absentee ballot.</a
		>
	</li>
</ul>

<h2>Endorsed Candidates</h2>
<div id="endorsed-races">
	<ul class="races">
		<li>
			<h3>President and Vice President</h3>
			<ul class="candidates">
				<li>
					<div class="candidate">
						<div class="picture">
							<img src="/images/candidates/2024/jbiden.jpg" alt="Joe Biden" />
						</div>
						<div class="name">President Joe Biden</div>
					</div>
					<div class="race">President</div>
				</li>
				<li>
					<div class="candidate">
						<div class="picture">
							<img src="/images/candidates/2024/kharris.jpg" alt="Kamala Harris" />
						</div>
						<div class="name">Vice President Kamala Harris</div>
					</div>
					<div class="race">Vice President</div>
				</li>
			</ul>
		</li>
		<li>
			<h3>Statewide Offices</h3>
			<ul class="candidates">
				<li>
					<div class="candidate">
						<div class="picture">
							<img src="/images/candidates/2024/bcasey.jpg" alt="Bob Casey" />
						</div>
						<div class="name">Sen. Bob Casey</div>
					</div>
					<div class="race">U.S. Senate</div>
				</li>
				<li>
					<div class="candidate">
						<div class="picture">
							<img src="/images/candidates/2024/rbizzarro.jpg" alt="Ryan Bizzarro" />
						</div>
						<div class="name">Rep. Ryan Bizzarro</div>
					</div>
					<div class="race">PA Treasurer</div>
				</li>
				<li>
					<div class="candidate">
						<div class="picture">
							<img src="/images/candidates/2024/mkenyatta.jpg" alt="Malcolm Kenyatta" />
						</div>
						<div class="name">Rep. Malcolm Kenyatta</div>
					</div>
					<div class="race">PA Auditor General</div>
				</li>
				<li />
			</ul>
		</li>
		<li>
			<h3>Congressional Representative</h3>
			<ul class="candidates">
				<li>
					<div class="candidate">
						<div class="picture">
							<img src="/images/candidates/2024/mdean.jpg" alt="Madeleine Dean" />
						</div>
						<div class="name">Rep. Madeleine Dean</div>
					</div>
					<div class="race">US Congress, 4th Congressional District</div>
				</li>
			</ul>
		</li>
		<li>
			<h3>State Legislature</h3>
			<ul class="candidates">
				<li>
					<div class="candidate">
						<div class="picture">
							<img src="/images/candidates/2024/nnelson.jpg" alt="Napoleon Nelson" />
						</div>
						<div class="name">Rep. Napoleon Nelson</div>
					</div>
					<div class="race">PA House of Representatives, 154th District</div>
				</li>
			</ul>
		</li>
	</ul>
</div>

<h2>Open Races</h2>
<div id="open-races">
	<ul class="races">
		<li>
			<h3>PA Attorney General</h3>
			<div class="description">
				Please vote for any <strong><em>one</em></strong> of these highly qualified candidates:
			</div>
			<ul class="candidates">
				<li>
					<div class="candidate">
						<div class="picture">
							<img src="/images/candidates/2024/kbradfordgrey.jpg" alt="Keir Bradford-Grey" />
						</div>
						<div class="name">Keir Bradford-Grey</div>
					</div>
					<div class="race">PA Attorney General</div>
				</li>
				<li>
					<div class="candidate">
						<div class="picture">
							<img src="/images/candidates/2024/edepasquale.png" alt="Eugene DePasquale" />
						</div>
						<div class="name">Eugene DePasquale</div>
					</div>
					<div class="race">PA Attorney General</div>
				</li>
				<li>
					<div class="candidate">
						<div class="picture">
							<img src="/images/candidates/2024/jkahn.jpg" alt="Joe Kahn" />
						</div>
						<div class="name">Joe Kahn</div>
					</div>
					<div class="race">PA Attorney General</div>
				</li>
				<li>
					<div class="candidate">
						<div class="picture">
							<img src="/images/candidates/2024/jsolomon.jpg" alt="Jared Solomon" />
						</div>
						<div class="name">Jared Solomon</div>
					</div>
					<div class="race">PA Attorney General</div>
				</li>
				<li>
					<div class="candidate">
						<div class="picture">
							<img src="/images/candidates/2024/jstollsteimer.jpg" alt="Jack Stollsteimer" />
						</div>
						<div class="name">Jack Stollsteimer</div>
					</div>
					<div class="race">PA Attorney General</div>
				</li>
				<li />
			</ul>
		</li>
	</ul>
</div>

<style>
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

	ul.candidates {
		list-style: none;
		display: flex;
		flex-wrap: wrap;
		padding: 5px;
		margin: 0px;
	}

	ul.candidates li {
		min-width: 300px;
		padding: 0px 10px;
		margin-top: 20px;
		flex: 1 0 calc(50% - 20px);
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
		max-width: 300px;
		max-height: 300px;
		overflow: hidden;
	}

	div.picture img {
		max-width: 100%;
		overflow: hidden;
		object-fit: cover;
	}

	div.description {
		text-align: center;
		font-style: italic;
	}
</style>
