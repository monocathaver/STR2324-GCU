<title>Home Page</title>

<script>
	let user_email = '';
</script>

<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<form method="POST">
	<label>
		Email
		<input name="email" type="email">
	</label>
	<label>
		Password  
		<input name="password" type="password">
	</label>
	<button>Log in</button>
</form>