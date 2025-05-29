<template>
  <div id="problemas" class="bg-white min-h-screen text-black flex flex-col items-center justify-center py-8 px-5">
    <section class="bg-white p-7 rounded-2xl w-full max-w-7xl">
      <h1 class="text-3xl text-azul-escuro md:text-4xl font-bold mb-7 text-center">
        Problemas Comuns e Diagnóstico de DNS
      </h1>

      <div>

      </div>
      <div class="grid gap-7 grid-cols-1 md:grid-cols-2">

        <!-- Card 1 -->
        <div class="flex flex-col">
          <h2 class="text-2xl font-bold bg-[#1c2b78] text-white rounded-t-xl py-3 px-4">
            Erros Comuns
          </h2>
          <div class="shadow-xl rounded-b-xl p-5 flex-1">
            <div class="space-y-5 text-[15px] text-azul-claro">
              <div>
                <h3 class="text-xl font-semibold mb-1">
                  Cache DNS desatualizado
                </h3>
                <p>
                  Às vezes, seu computador ou o servidor DNS guarda informações antigas, o que pode impedir o acesso a
                  um site recém-migrado ou atualizado.
                </p>
              </div>
              <div>
                <h3 class="text-xl font-semibold mb-1">
                  Erro no arquivo de zona
                </h3>
                <p>
                  Os arquivos de zona controlam os registros do domínio. Um erro de digitação, registros faltando ou
                  duplicados podem fazer tudo parar de funcionar.
                </p>
              </div>
              <div>
                <h3 class="text-xl font-semibold mb-1">
                  TTL (Time To Live) mal configurado
                </h3>
                <p>
                  TTL define quanto tempo os registros ficam guardados no cache. Se for muito alto, dificulta
                  atualizações. Se for muito baixo, gera tráfego desnecessário.
                </p>
              </div>
            </div>
          </div>
        </div>

        <!-- Card 2 -->
        <div class="flex flex-col">
          <h2 class="text-2xl font-bold bg-[#1c2b78] text-white rounded-t-xl py-3 px-4">
            Ferramentas para Diagnóstico
          </h2>
          <div class="shadow-xl rounded-b-xl p-5 flex-1 text-azul-claro">
            <ul class="list-disc space-y-4 ml-5 text-[15px]">
              <li><span class="underline">nslookup</span>: simples e direto, mostra o IP de um domínio.</li>
              <li><span class="underline">dig</span>: mais completo, ótimo para detalhes técnicos e rastrear a origem
                dos problemas.</li>
              <li><span class="underline">ping</span>: testa se o domínio resolve e responde.</li>
              <li><span class="underline">traceroute / tracert</span>: mostra o caminho até o servidor. Útil se o
                problema não for no DNS, mas na rede.</li>
            </ul>
          </div>
        </div>

        <!-- Card 3 -->
        <div class="col-span-1 md:col-span-2 ">
          <h2 class="text-2xl font-bold bg-[#1c2b78] text-white rounded-t-xl py-3 px-4">
            Boas Práticas para Configuração de DNS
          </h2>
          <div class="shadow-xl rounded-b-xl p-5 text-azul-claro">
            <ul class="list-disc space-y-4 ml-5 text-[15px]">
              <li>Sempre documente as mudanças.</li>
              <li>Escolha um TTL equilibrado.</li>
              <li>Tenha mais de um servidor DNS (redundância).</li>
              <li>Use DNSSEC se possível, para mais segurança.</li>
              <li>Monitore os logs e valide as zonas antes de publicar.</li>
            </ul>
          </div>
        </div>

      </div>


    </section>

  </div>
</template>
