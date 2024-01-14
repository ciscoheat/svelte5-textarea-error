<script lang="ts">
	import { writable } from 'svelte/store';
	const msg = writable('');
</script>

<textarea bind:value={$msg} />
