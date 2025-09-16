<script lang="ts">
  import fgarden from "$lib/assets/fgarden.svg";
  import logo from "$lib/assets/logo.svg";
  import ig from "$lib/assets/ig.svg";
</script>

<div class="flex-1 flex flex-col items-center justify-around p-4">
  <div class="flex flex-col gap-4 text-center text-2xl font-bold uppercase">
    <img
      src={logo}
      alt="Rede Memória"
      class="w-full max-w-64 h-full max-h-64"
    />
    <h1>Rede Memória</h1>
  </div>

  <div class="text-center max-w-lg space-y-4 gap-1">
    <h2 class="mb-4">Preservação, Educação e Cruzamento de Arquivos</h2>
    <p>
      Uma iniciativa transnacional que conecta arquivos, instituições e
      comunidades lusófonas para preservar e reinterpretar nossa memória
      coletiva.
    </p>
    <p>
      Criamos pontes entre documentos dispersos no Brasil, Portugal e PALOP,
      reconstruindo narrativas apagadas e democratizando o acesso ao
      conhecimento histórico.
    </p>
    <p>
      Transformamos a preservação em ação participativa, onde comunidades se
      tornam protagonistas na construção de novas leituras sobre o passado.
    </p>
  </div>

  <div class="flex justify-between items-center mt-4 w-full max-w-md">
    <div>
      <a
        href="https://instagram.com/redememoria"
        target="_blank"
        rel="noopener noreferrer"
        class="hover:opacity-80 transition-opacity"
      >
        <img src={ig} alt="Siga no Instagram" class="w-8 h-8" />
      </a>
    </div>
    <div>
      <span class="text-xs">um projeto</span>
      <img src={fgarden} alt="f.garden" class="inline w-6 ml-1" />
    </div>
  </div>
</div>
