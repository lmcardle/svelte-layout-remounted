<script>
	import { goto } from '$app/navigation';

	function buttonClick() {
		goto('/foo');
	}
</script>

<button on:click={buttonClick}>Click to goto Foo</button>
