<script>
	import { browser } from '$app/env';
</script>

{#if browser}
  <!-- Include the script that builds the page and powers Netlify CMS -->
  <script src="https://unpkg.com/netlify-cms@^2.0.0/dist/netlify-cms.js"></script>
{/if}