<script>
	import 'virtual:windi.css';
	import { browser } from '$app/env';
	// @ts-ignore: Cannot find module 'virtual:windi-devtools' or its corresponding type declarations.
	if (browser) import('virtual:windi-devtools');
</script>

<main>
	<slot />
</main>
