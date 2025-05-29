<template>
  <div id="dominioendereco" class="flex min-h-screen w-full flex-col items-center justify-center bg-white py-10 px-4">
    <h1 class="mb-8 text-3xl md:text-5xl font-bold text-center text-azul-escuro">
      Tradução de Nomes de Domínio em Endereços IP
    </h1>

    <div class="flex flex-wrap justify-center gap-8 md:gap-10">

      <!-- Funcionamento do DNS -->
      <div class="flex w-80 flex-col rounded-2xl bg-white shadow-xl">
        <h2 class="bg-azul-claro rounded-t-2xl px-6 py-4 text-lg md:text-xl font-semibold text-white">
          Funcionamento do DNS
        </h2>
        <div class="flex flex-1 items-center justify-center px-6 py-4">
          <p class="text-base text-gray-700">
            O DNS funciona como uma agenda da internet, convertendo nomes de domínio (como google.com) em endereços IP,
            permitindo que o navegador encontre o servidor correto.
          </p>
        </div>
      </div>

      <!-- Hierarquia do DNS -->
      <div class="flex w-80 flex-col rounded-2xl bg-white shadow-xl">
        <h2 class="bg-azul-claro rounded-t-2xl px-6 py-4 text-lg md:text-xl font-semibold text-white">
          Hierarquia do DNS
        </h2>
        <div class="flex flex-1 items-center justify-center px-6 py-4">
          <ul class="list-disc list-inside text-base text-gray-700">
            <li>Servidores Raiz</li>
            <li>Domínios de Topo (TLD)</li>
            <li>Servidores Autoritativos</li>
          </ul>
        </div>
      </div>

      <!-- Processo de Resolução de Nomes -->
      <div class="flex w-full max-w-3xl flex-col rounded-2xl bg-white shadow-xl">
        <h2 class="bg-azul-claro rounded-t-2xl px-6 py-4 text-lg md:text-2xl font-semibold text-white">
          Processo de Resolução de Nomes
        </h2>
        <div class="flex flex-1 justify-center px-6 py-4">
          <ol class="list-decimal list-inside text-base text-gray-700 space-y-2">
            <li>O navegador consulta o resolvedor recursivo (geralmente do provedor ou Google DNS/Cloudflare).</li>
            <li>O resolvedor consulta um servidor raiz para saber onde está o TLD (.com, .br, etc.).</li>
            <li>O servidor raiz responde indicando o servidor TLD.</li>
            <li>O resolvedor consulta o TLD, que responde com os servidores autoritativos do domínio.</li>
            <li>O servidor autoritativo retorna o IP correspondente ao domínio.</li>
            <li>O resolvedor envia o IP ao navegador, que então acessa o site.</li>
          </ol>
        </div>
      </div>

      <!-- Como o Navegador Inicia uma Consulta DNS -->
      <div class="flex w-80 flex-col rounded-2xl bg-white shadow-xl">
        <h2 class="bg-azul-claro rounded-t-2xl px-6 py-4 text-lg md:text-xl font-semibold text-white">
          Como o Navegador Inicia uma Consulta DNS
        </h2>
        <div class="flex flex-1 items-center justify-center px-6 py-4">
          <p class="text-base text-gray-700">
            O navegador busca no cache local. Se não encontrar, aciona o servidor DNS, que consulta servidores raiz, TLD
            e autoritativos até obter a resposta certa.
          </p>
        </div>
      </div>

      <!-- Resolução Recursiva vs Iterativa -->
      <div class="flex w-80 flex-col rounded-2xl bg-white shadow-xl">
        <h2 class="bg-azul-claro rounded-t-2xl px-6 py-4 text-lg md:text-xl font-semibold text-white">
          Resolução Recursiva vs Iterativa
        </h2>
        <div class="flex flex-1 items-center justify-center px-6 py-4">
          <p class="text-base text-gray-700">
            Recursiva: o servidor faz tudo e entrega pronto. Iterativa: o cliente recebe instruções e faz consultas
            sucessivas até obter a resposta.
          </p>
        </div>
      </div>

      <!-- Função dos Servidores DNS -->
      <div class="flex w-80 flex-col rounded-2xl bg-white shadow-xl">
        <h2 class="bg-azul-claro rounded-t-2xl px-6 py-4 text-lg md:text-xl font-semibold text-white">
          Função dos Servidores DNS
        </h2>
        <div class="flex flex-1 items-center justify-center px-6 py-4">
          <p class="text-base text-gray-700">
            Servidor raiz → aponta para o TLD. TLD → aponta para o servidor autoritativo. Autoritativo → entrega o IP
            real do domínio.
          </p>
        </div>
      </div>

      <!-- Coluna com 2 cards menores -->
      <div class="flex flex-col gap-8">

        <!-- Card Raiz -->
        <div class="flex w-80 flex-col rounded-2xl bg-white shadow-xl">
          <h2 class="bg-azul-claro rounded-t-2xl px-6 py-4 text-lg md:text-xl font-semibold text-white">
            Servidor Raiz
          </h2>
          <div class="flex flex-1 items-center justify-center px-6 py-4">
            <p class="text-base text-gray-700">
              Não entrega o IP, mas indica os servidores de alto nível (.com, .br, .org), guiando a busca para o próximo
              nível.
            </p>
          </div>
        </div>

        <!-- Card TLD -->
        <div class="flex w-80 flex-col rounded-2xl bg-white shadow-xl">
          <h2 class="bg-azul-claro rounded-t-2xl px-6 py-4 text-lg md:text-xl font-semibold text-white">
            Servidor de Alto Nível (TLD)
          </h2>
          <div class="flex flex-1 items-center justify-center px-6 py-4">
            <p class="text-base text-gray-700">
              Guarda informações dos domínios de topo, como .com, .net, .org ou códigos de país (.br, .uk, .jp, etc.).
            </p>
          </div>
        </div>

      </div>
    </div>
  </div>
</template>
