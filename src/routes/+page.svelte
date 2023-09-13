<h1>Welcome to SvelteKit</h1>

<script>
	let name = '';
</script>

<input bind:value={name} placeholder="enter your name" />
<p>Hello {name || 'stranger'}!</p>

<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
