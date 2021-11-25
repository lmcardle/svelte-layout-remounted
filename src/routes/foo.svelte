<script>
	import { goto } from '$app/navigation';

	function buttonClick() {
		goto('/');
	}
</script>

<button on:click={buttonClick}>Click to goto Home</button>
