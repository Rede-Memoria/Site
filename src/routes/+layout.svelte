<script lang="ts">
  import "../app.css";
  import favicon from "$lib/assets/logo.svg";

  let { children } = $props();
</script>

<svelte:head>
  <link rel="icon" href={favicon} />
</svelte:head>

<main
  class="min-h-screen flex flex-col bg-gradient-to-b from-[#471C05] via-[#f4dfc2] to-[#f4dfc2]"
>
  {@render children?.()}
</main>
