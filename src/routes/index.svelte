<script lang="ts">
	import { onMount } from 'svelte';

	let canvas: HTMLCanvasElement;

	onMount(() => {
		console.log(canvas);
	});
</script>

<div>
	<canvas id="main-canvas" bind:this={canvas} />
</div>
