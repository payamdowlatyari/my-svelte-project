<script lang="ts">
	export let name: string;
</script>

<main>
	<nav>
		<h1>I am {name}</h1>
	</nav>

	<p>
		Visit my website at <a href="https://www.payamd.com">payamd.com</a> for more
		information
	</p>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
		background-color: #222;
		height: 100vh;
	}

	h1 {
		color: chocolate;
		opacity: 0.5;
		font-size: 4em;
		font-weight: 500;
	}

	p {
		color: darkgrey;
		font-weight: 100;
	}

	a {
		color: #ddd;
		font-weight: bolder;
	}

	a:hover {
		text-decoration: none;
		color: #fff;
		transition: 0.5s;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
