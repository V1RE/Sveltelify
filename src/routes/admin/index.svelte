<script>
	import { onMount } from 'svelte';
	import 'netlify-identity-widget';

	onMount(async () => {
		const CMS = await import('netlify-cms-app');
		CMS.init();
	});
</script>
