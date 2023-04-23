<script>
	export let answer = true;
</script>

<div class="wrapper {answer ? 'correct' : 'incorrect'}">
{#if answer}
	<h1>Good job!</h1>
{:else}
	<h2>Not quite...</h2>
{/if}
</div>
<style>
	.correct,
	.incorrect {
		font-weight: bold;
		text-decoration: underline;
	}
</style>