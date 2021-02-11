<script>
	import Dashboard from './components/dashboard.svelte';
	export let name;
</script>

<Dashboard />


<style global lang="postcss">
  /* only apply purgecss on utilities, per Tailwind docs */
  @tailwind base;
  @tailwind components;
  @tailwind utilities;

</style>