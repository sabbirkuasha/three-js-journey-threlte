<script lang="ts">
	import { Canvas } from '@threlte/core';
	// import Scene from './53-create-a-game-with-threlte/Experience.svelte';
	// import Scene from './52-physics-with-threlte/Experience.svelte';
	// import Scene from './51-fun-and-simple-portfolio/Experience.svelte';
	// import Scene from './50-post-processing-with-threlte/Experience.svelte';
	// import Scene from './49-mouse-events-with-threlte/Experience.svelte';
	// import Scene from './48-portal-scene-with-threlte/Experience.svelte';
	// import Scene from './47-3d-text-with-threlte/Experience.svelte';
	// import Scene from './46-load-models-with-threlte/Experience.svelte';
	// import Scene from './45-environment-and-staging/Experience.svelte';
	// import Scene from './43-threlte-extras/Experience.svelte';
	import Scene from './42-first-threlte-application/Experience.svelte';
	import Interface from './53-create-a-game-with-threlte/Interface.svelte';
	import { KeyboardControls, wasdConfig } from 'svelte-kbc';
</script>

<KeyboardControls config={wasdConfig()}>
	<!-- <Interface /> -->
	<Canvas>
		<Scene />
	</Canvas>
</KeyboardControls>
