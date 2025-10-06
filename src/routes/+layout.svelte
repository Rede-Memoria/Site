<script lang="ts">
  import "../app.css";

  let { children } = $props();
</script>

<svelte:head>
  <link rel="icon" href="//_app/immutable/assets/favicon.ico" />

  <!-- Primary Meta Tags -->
  <title>Rede Memória - Preservação, Educação e Cruzamento de Arquivos</title>
  <meta
    name="title"
    content="Rede Memória - Preservação, Educação e Cruzamento de Arquivos"
  />
  <meta
    name="description"
    content="Uma iniciativa transnacional que conecta arquivos, instituições e comunidades lusófonas para preservar e reinterpretar nossa memória coletiva."
  />

  <!-- Open Graph / Facebook -->
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://redememoria.org" />
  <meta
    property="og:title"
    content="Rede Memória - Preservação, Educação e Cruzamento de Arquivos"
  />
  <meta
    property="og:description"
    content="Uma iniciativa transnacional que conecta arquivos, instituições e comunidades lusófonas para preservar e reinterpretar nossa memória coletiva."
  />
  <meta
    property="og:image"
    content="https://redememoria.org//_app/immutable/assets/LOGO_AMPULHETA.png"
  />
  <meta property="og:image:width" content="1024" />
  <meta property="og:image:height" content="1024" />
  <meta property="og:locale" content="pt" />

  <!-- Twitter -->
  <meta property="twitter:card" content="summary_large_image" />
  <meta property="twitter:url" content="https://redememoria.org" />
  <meta
    property="twitter:title"
    content="Rede Memória - Preservação, Educação e Cruzamento de Arquivos"
  />
  <meta
    property="twitter:description"
    content="Uma iniciativa transnacional que conecta arquivos, instituições e comunidades lusófonas para preservar e reinterpretar nossa memória coletiva."
  />
  <meta
    property="twitter:image"
    content="https://redememoria.org//_app/immutable/assets/LOGO_AMPULHETA.png"
  />

  <!-- WhatsApp specific -->
  <meta property="og:image:type" content="image/png" />
  <meta property="og:site_name" content="Rede Memória" />

  <!-- Additional SEO -->
  <meta
    name="keywords"
    content="memória, arquivo, história, Portugal, Brasil, PALOP, preservação, educação, documentos"
  />
  <meta name="author" content="Rede Memória" />
  <meta name="robots" content="index, follow" />
  <meta name="language" content="Portuguese" />
  <meta name="revisit-after" content="7 days" />
</svelte:head>

<main
  class="min-h-screen flex flex-col bg-gradient-to-b from-[#471C05] via-[#f4dfc2] to-[#f4dfc2]"
>
  {@render children?.()}
</main>
