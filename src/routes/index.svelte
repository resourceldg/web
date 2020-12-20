<style>
	h1, figure, p {
		text-align: center;
		margin: 0 auto;
	}

	h1 {
		font-size: 2.8em;
		font-weight: 400;
		margin: 0 0 0.5em 0;
	}

	figure {
		margin: 0 0 1em 0;
	}

	img {
		width: 100%;
		max-width: 400px;
		margin: 0 0 1em 0;
	}

	p {
		margin: 1em auto;
		padding-bottom: 1em;
	}

	@media (min-width: 480px) {
		h1 {
			font-size: 4em;
		}
	}
</style>
<script>
import "tailwindcss/tailwind.css"
</script>
<svelte:head>
	<title>a minimal sapper blog</title>
</svelte:head>
<p>welcome to</p>
<h1>the<b>blog.</b></h1>
<div class="p-6 max-w-sm mx-auto bg-blue-300 rounded-xl shadow-md flex items-center space-x-4">
	<div class="flex-shrink-0">
	  <img class="h-12 w-12" src="/img/logo.svg" alt="ChitChat Logo">
	</div>
	<div>
	  <div class="text-xl font-medium text-black">ChitChat</div>
	  <p class="text-gray-500">You have a new message!</p>
	</div>
  </div>

<figure>
	<img alt='the birds on a line' src='bird-bg.png'>
	<figcaption>where less is more</figcaption>
</figure>

<p><strong>we're minimal and that might seem boring, except you're actually paying attention.</strong></p>
<p class="link"><a href="about">find out why</a>...</p>