<script>
	import { onMount } from 'svelte';

	onMount(() => {
		console.log('running onMount');
	});
</script>

<div>
	<a href="/">Home</a>
	<span>|</span>
	<a href="/foo">Foo</a>
</div>
<slot />
