<script>
	import Email from './icons/Email.svelte';
	import Github from './icons/Github.svelte';
	import Resume from './icons/Resume.svelte';
</script>

<main>
	<h1>BRIAN</h1>

	<section>
		<ul>
			<li>
				<span class='icon'>
					<a href='https://docs.google.com/document/d/1sjnzkNS2D0vEDKCjEcHA8uDVWOidFkW1gsh4ae_EltI/edit?usp=sharing'><Resume /></a>
				</span>
				<span><a href='https://docs.google.com/document/d/1sjnzkNS2D0vEDKCjEcHA8uDVWOidFkW1gsh4ae_EltI/edit?usp=sharing'>resume</a></span>
			</li>

			<li>
				<span class='icon'>
					<a href='https://github.com/bduimstra'><Github /></a>
				</span>
				<span><a href='https://github.com/bduimstra'>github</a></span>
			</li>

			<li>
				<span class='icon'>
					<a href='mailto:brian@duimstra.io'><Email /></a>
				</span>
				<span><a href='mailto:brian@duimstra.io'>brian@duimstra.io</a></span>
			</li>
		</ul>
	</section>
</main>

<footer>
	<a href='mailto:brian@duimstra.io'>Get at me.</a>
</footer>