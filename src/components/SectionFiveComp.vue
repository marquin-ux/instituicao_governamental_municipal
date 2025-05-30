<template>
  <section id="contexto"
    class="bg-azul-escuro min-h-screen w-full flex flex-col justify-center items-center gap-10 px-6 py-10 rounded-lg shadow-lg">
    <!-- Título -->
    <h1 class="text-4xl font-bold text-white drop-shadow-md">
      Contexto do Projeto
    </h1>

    <!-- Bloco 1 -->
    <div class="flex flex-col xl:flex-row gap-8 w-3/4 max-w-7xl items-center">
      <img src="../assets/images/gob-br.jpg" alt="Imagem Pastor Cícero"
        class="w-full xl:w-2/5 rounded-lg object-cover shadow-md" />

      <div class="flex flex-col gap-4 w-full xl:w-3/5">
        <p class="text-lg text-white drop-shadow-sm leading-relaxed">
          Como instituição governamental, é preciso ter acesso a sistemas e
          serviços de forma eficiente, segura e amigável. O DNS ajuda nesses
          aspectos, uma vez que, após a efetivação de sua tradução de endereços
          IP, os nomes ficam mais fáceis de memorizar, o que melhora
          significativamente a usabilidade para os usuários, reduz erros de
          digitação e agiliza o acesso a portais e plataformas, tornando isso
          possível.
          <br /><br />
          O DNS organiza o acesso aos domínios de forma centralizada, o que
          contribui para o manuseamento da rede de uma forma mais eficiente e
          segura. Essa função permite que os administradores tenham um controle
          maior sobre o direcionamento de tráfego interno e externo, assim,
          podendo aplicar políticas de segurança e segmentação de forma mais
          eficaz.
        </p>
      </div>
    </div>

    <!-- Bloco 2 -->
    <div class="flex flex-col md:flex-row-reverse gap-8 w-3/4 max-w-7xl items-center">
      <img src="../assets/images/diagrama.jpg" alt="Diagrama de Redes"
        class="w-2/3 md:w-2/4 rounded-lg object-cover shadow-md" />

      <div class="flex flex-col gap-4 w-full md:w-5/5">
        <p class="text-lg text-white drop-shadow-sm leading-relaxed">
          Por fim, o DNS ao atuar de maneira integrada entre diferentes setores
          (como saúde, educação e segurança), que são divididos e identificados
          como por exemplo: “.gov”, “.edu”, “@seguranca” e “@saude”; garantindo
          a padronização do acesso e facilitando a comunicação entre sistemas
          distintos, identificados pelos DNS root (raiz), DNS .com, e pelo DNS
          do site.com, promovendo interoperabilidade e escalabilidade dentro da
          infraestrutura de rede.
        </p>
      </div>
    </div>
    <div class="flex justify-center w-full px-6">
      <img src="../assets/images/root.png" alt="DNS Root"
        class="rounded-lg shadow-md max-w-[500px] w-full object-contain" />
    </div>


  </section>
</template>
