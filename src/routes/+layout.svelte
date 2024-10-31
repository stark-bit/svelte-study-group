<script lang="ts">
	import '../app.css';
  import '$lib/cat';
	let { children } = $props();
  import { page } from '$app/stores'


</script>

<div class='flex bg-green-500 p-4 font-black justify-between'>
<a href="/"><h1 class="">iVendi FE Study group</h1></a>
  <span class=''>{$page.route.id?.slice(1)?.toUpperCase()} </span>
</div>
<main class="prose mx-auto py-[4rem]">
  {@render children()}
</main>

