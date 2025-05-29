<template>
  <div id="fontes" class="bg-azul-escuro min-h-screen text-white flex flex-col items-center justify-center py-8 px-4">
    <section class="p-4 rounded-2xl shadow-xl w-full max-w-6xl bg-[#1c2b78]">
      <h1 class="text-2xl md:text-3xl font-bold mb-6 text-center">
        Fontes de Pesquisa sobre DNS
      </h1>

      <div class="space-y-4">
        <!-- Card Google DNS -->
        <div class="bg-[#24308a] rounded-xl p-5">
          <h2 class="text-xl font-bold mb-3">
            Funcionamento do Google DNS
          </h2>
          <p class="mb-2 text-[15px]">
            Explica como o Google DNS atua como servidor recursivo e o processo de cache e resolução.
          </p>
          <a href="https://developers.google.com/speed/public-dns/docs/intro" target="_blank"
            class="underline text-blue-300 hover:text-blue-400">
            Link: Google Public DNS
          </a>
        </div>

        <!-- Card Cloudflare -->
        <div class="bg-[#24308a] rounded-xl p-5">
          <h2 class="text-xl font-bold mb-3">
            Funcionamento Geral do DNS
          </h2>
          <p class="mb-2 text-[15px]">
            Explica resolução recursiva e iterativa, tipos de servidores (Raiz, TLD, Autoritativo) e todo o fluxo da
            consulta DNS.
          </p>
          <a href="https://www.cloudflare.com/learning/dns/what-is-dns/" target="_blank"
            class="underline text-blue-300 hover:text-blue-400">
            Link: Cloudflare
          </a>
        </div>

        <!-- Card MDN -->
        <div class="bg-[#24308a] rounded-xl p-5">
          <h2 class="text-xl font-bold mb-3">
            Resolução de Domínios no Navegador
          </h2>
          <p class="mb-2 text-[15px]">
            Descreve como o navegador resolve domínios, cache local, e interação com o sistema operacional.
          </p>
          <a href="https://developer.mozilla.org/en-US/docs/Glossary/DNS" target="_blank"
            class="underline text-blue-300 hover:text-blue-400">
            Link: MDN Web Docs
          </a>
        </div>

        <!-- Card Problemas Comuns -->
        <div class="bg-[#24308a] rounded-xl p-5">
          <h2 class="text-xl font-bold mb-3">
            Problemas Comuns em DNS
          </h2>
          <ul class="list-disc ml-5 space-y-2 text-[15px]">
            <li>
              <a href="https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/Welcome.html" target="_blank"
                class="underline text-blue-300 hover:text-blue-400">
                AWS Route 53
              </a>
            </li>
            <li>
              <a href="https://registro.br/tecnologia/caracteristicas-tecnicas/" target="_blank"
                class="underline text-blue-300 hover:text-blue-400">
                Registro.br
              </a>
            </li>
            <li>
              <a href="https://pt.wikipedia.org/wiki/Sistema_de_Nomes_de_Dom%C3%ADnio" target="_blank"
                class="underline text-blue-300 hover:text-blue-400">
                Wikipedia - Sistema de Nomes de Domínio
              </a>
            </li>
            <li>
              <a href="https://suporte.hostgator.com.br/hc/pt-br/articles/30807977835795" target="_blank"
                class="underline text-blue-300 hover:text-blue-400">
                HostGator - Suporte
              </a>
            </li>
            <li>
              <a href="https://www.cherokee.com.br/blog/artigos/entendendo-o-dns-o-alicerce-da-internet-moderna"
                target="_blank" class="underline text-blue-300 hover:text-blue-400">
                Cherokee - Entendendo o DNS
              </a>
            </li>
          </ul>
        </div>

        <!-- Rodapé -->
        <div class="bg-[#192569] rounded-xl p-3 text-center">
          <p class="text-sm">
            Fontes confiáveis para estudo e compreensão do DNS e seus problemas comuns.
          </p>
        </div>

      </div>
    </section>
  </div>
</template>
