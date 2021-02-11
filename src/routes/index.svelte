<script>
  import { Example  } from '@inspired-devs/ui-base/src';
  const name = 'World';
</script>

<style lang="postcss">
  .btn {
    @apply bg-red-500 text-red-100 uppercase tracking-wide font-semibold
      text-4xl px-4 py-3 shadow-lg rounded;
  }
</style>

<svelte:head>
	<title>Sapper project template</title>
</svelte:head>

<div class="space-y-10 text-center">
  <h1 class="text-7xl uppercase font-bold">Great success!</h1>
  <Example {name} />
  <button class="btn">DO NOT PRESS THIS BUTTON!</button>
</div>