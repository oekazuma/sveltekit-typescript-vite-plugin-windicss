<script>
  import 'virtual:windi.css';
  import { browser } from '$app/env';
  if (browser) import('virtual:windi-devtools');
</script>

<main>
  <slot />
</main>
