<template>
  <div id="contexto">
    <section
      class="bg-azul-escuro flex flex-col justify-center items-center gap-8 p-8 w-full min-h-screen mx-auto rounded-lg shadow-lg">
      <!-- Título -->
      <h1 class="text-4xl font-bold mb-6 text-white drop-shadow-md">
        Contexto do Projeto
      </h1>

      <!-- Primeira seção: imagem + texto -->
      <div class="flex flex-col xl:flex-row text-cente justify-center items-center gap-6 w-full xl:px-35">
        <img class="w-full xl:w-2/5 rounded-lg object-cover shadow-md" src="../assets/images/gob-br.jpg"
          alt="Imagem Pastor Cícero" />
        <div class="flex flex-col justify-center items-center xl:items-start gap-4 w-full xl:w-3/5 px-4">
          <p class="text-lg max-xl:text-base text-white drop-shadow-sm leading-relaxed xl:px-2">
            Como instituição governamental, é preciso ter acesso a sistemas e
            serviços de forma eficiente, segura e amigável. O DNS ajuda nesses
            aspectos, uma vez que, após a efetivação de sua tradução de endereços
            IP, os nomes ficam mais fáceis de memorizar, o que melhora
            significativamente a usabilidade para os usuários, reduz erros de
            digitação e agiliza o acesso a portais e plataformas, tornando isso
            possível.
            <br>
            <br>
            O DNS organiza o acesso aos domínios de forma centralizada, o que
            contribui para o manuseamento da rede de uma forma mais eficiente e
            segura. Essa função permite que os administradores tenham um controle
            maior sobre o direcionamento de tráfego interno e externo, assim,
            podendo aplicar políticas de segurança e segmentação de forma mais
            eficaz.
          </p>
        </div>
      </div>

      <!-- Segunda seção: imagem + texto, imagem à direita -->
      <div class="flex flex-col md:flex-row-reverse justify-center items-center gap-6 w-full p-4">
        <img class="w-1/2 md:w-1/4 rounded-lg object-cover shadow-md" src="../assets/images/diagrama.jpg"
          alt="Diagrama de Redes" />

        <div class="flex flex-col justify-center items-center md:items-start gap-4 w-full md:w-3/5 px-4">
          <p class="text-lg max-md:text-base text-white drop-shadow-sm leading-relaxed">
            Por fim, o DNS ao atuar de maneira integrada entre diferentes setores
            (como saúde, educação e segurança), que são divididos e identificados
            como por exemplo: “.gov”, “.edu”, “@seguranca” e “@saude”; Garantindo
            a padronização do acesso e facilitando a comunicação entre sistemas
            distintos, identificados pelos DNS root (raiz), DNS .com, e pelo DNS
            do site.com, promovendo interoperabilidade e escalabilidade dentro
            da infraestrutura de rede.
          </p>
        </div>
      </div>
    </section>
  </div>
</template>
