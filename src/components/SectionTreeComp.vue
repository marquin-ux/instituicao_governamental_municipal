<template>
  <div id="dns" class="bg-azul-escuro min-h-screen text-white py-8 px-5 justify-center items-center flex flex-col">

    <!-- Título -->
    <h1 class="text-4xl font-bold mb-10 text-center">
      Importância do DNS para a Usabilidade da Internet
    </h1>

    <!-- Grid principal -->
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-10 items-center mb-10">

      <!-- Imagem -->
      <div class="flex justify-center items-center max-w-2xl mx-auto">
        <img src="../assets/images/DNS.jpg" alt="Imagem sobre DNS" class="w-full rounded-2xl">
      </div>

      <!-- Cards -->
      <div class="flex flex-col md:flex-row lg:flex-col gap-8 items-center max-w-2xl mx-auto">

        <!-- Card 1 -->
        <div class="bg-white text-black rounded-2xl shadow-2xl">
          <div class="bg-azul-claro py-6 px-4 rounded-t-2xl">
            <h2 class="text-2xl font-bold text-white text-center">
              Como o DNS facilita a navegação na internet
            </h2>
          </div>
          <div class="p-6">
            <p class="text-lg leading-relaxed">
              O DNS traduz nomes de sites em endereços IP, permitindo que os usuários acessem páginas usando nomes
              fáceis de lembrar. Sem ele, seria necessário decorar sequências numéricas para navegar na internet.
            </p>
          </div>
        </div>

        <!-- Card 2 -->
        <div class="bg-white text-black rounded-2xl shadow-2xl">
          <div class="bg-azul-claro py-6 px-4 rounded-t-2xl">
            <h2 class="text-2xl font-bold text-white text-center">
              Impacto na performance e escalabilidade da internet
            </h2>
          </div>
          <div class="p-6">
            <p class="text-lg leading-relaxed">
              Um sistema DNS eficiente melhora a velocidade de acesso aos sites e permite que a internet funcione de
              forma organizada e escalável, atendendo milhões de usuários ao mesmo tempo.
            </p>
          </div>
        </div>

      </div>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mx-auto max-w-[86.5rem]">

      <!-- DNSSEC -->
      <div class="bg-white text-black rounded-2xl shadow-2xl">
        <div class="bg-azul-claro py-4 px-4 rounded-t-2xl">
          <h3 class="text-xl font-bold text-white text-center">DNSSEC</h3>
        </div>
        <div class="p-5">
          <p><strong>O que é:</strong> Extensão do DNS que usa assinaturas digitais para garantir autenticidade e
            integridade.</p>
          <p class="mt-2"><strong>Como funciona:</strong> Usa criptografia de chave pública para assinar registros DNS,
            permitindo que sejam validados.</p>
          <p class="mt-2"><strong>Importância:</strong> Protege contra ataques como envenenamento de cache, mantendo
            usuários seguros.</p>
        </div>
      </div>

      <!-- DNS Spoofing -->
      <div class="bg-white text-black rounded-2xl shadow-2xl">
        <div class="bg-azul-claro py-4 px-4 rounded-t-2xl">
          <h3 class="text-xl font-bold text-white text-center">DNS Spoofing</h3>
        </div>
        <div class="p-5">
          <p><strong>O que é:</strong> Ataque que insere dados falsos no cache do DNS, retornando IPs incorretos.</p>
          <p class="mt-2"><strong>Consequências:</strong> Usuários são redirecionados para sites falsos, sofrendo
            phishing, malware e roubo de dados.</p>
          <p class="mt-2"><strong>Prevenção:</strong> Uso de DNSSEC, portas aleatórias e validação rigorosa das
            respostas DNS.</p>
        </div>
      </div>

      <!-- IP Spoofing -->
      <div class="bg-white text-black rounded-2xl shadow-2xl">
        <div class="bg-azul-claro py-4 px-4 rounded-t-2xl">
          <h3 class="text-xl font-bold text-white text-center">IP Spoofing</h3>
        </div>
        <div class="p-5">
          <p><strong>O que é:</strong> Técnica onde o atacante falsifica o IP de origem para mascarar sua identidade.
          </p>
          <p class="mt-2"><strong>Relação com DNS:</strong> Pode ser usado junto com DNS Spoofing para desviar tráfego
            ou interceptar dados.</p>
        </div>
      </div>
    </div>



  </div>
</template>
