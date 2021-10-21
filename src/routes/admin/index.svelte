<script>
  import { onMount } from 'svelte';
  import 'netlify-identity-widget';
  import CMS from 'netlify-cms-app';

  onMount(() => {
    CMS.init();
  });
</script>
