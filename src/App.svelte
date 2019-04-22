<script>
	let name = 'x';

	$: n = name || '!?'
</script>

<style>
	h1 {
		color: purple;
	}
</style>

<h1>h{n}</h1>
