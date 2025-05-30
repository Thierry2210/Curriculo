<template>
  <div class="container mx-auto p-4">
    <header class="text-center mb-8">
      <div class="flex justify-center mb-4">
        <img
          src="@/assets/img/IMG-20241117-WA0016.png"
          alt="Imagem de Matheus Thierry Santos da Silva"
          class="rounded-full w-32 h-32 object-cover border-4 border-sky-700 shadow-lg"
        />
      </div>
      <h1 class="text-4xl font-extrabold text-sky-700 mb-2">Matheus Thierry Santos da Silva</h1>
      <h2 class="text-xl text-gray-600 font-semibold">Aluno de ADS da Unimar</h2>
    </header>

    <main class="grid gap-6 md:grid-cols-2">
      <!-- Sobre mim -->
      <section class="bg-white rounded-lg shadow p-6 col-span-2">
        <h3 class="text-2xl font-bold text-sky-700 mb-3">Sobre mim</h3>
        <p class="text-gray-700 leading-relaxed">
          Olá, meu nome é Matheus Thierry Santos da Silva, tenho 19 anos e sou estudante de Análise e Desenvolvimento de Sistemas na Unimar. Sou apaixonado por programação e tecnologia, buscando sempre aprimorar meus conhecimentos em diversas áreas da área de TI. Tenho interesse em desenvolvimento de software, automação e inovação, e estou constantemente em busca de novos desafios.<br><br>
          Além de programar, também gosto de estudar sobre novas tecnologias, ler sobre temas diversos e explorar minha criatividade através do desenho. No meu tempo livre, gosto de ouvir músicas, o que me ajuda a relaxar e me concentrar melhor nas minhas atividades.<br><br>
          Estou sempre em busca de aprendizado contínuo e de oportunidades para aplicar o que estou aprendendo em projetos práticos, seja no contexto acadêmico ou em atividades extracurriculares. Acredito que a colaboração e o trabalho em equipe são fundamentais para alcançar soluções inovadoras, e sempre busco aprender com outros profissionais da área.
        </p>
      </section>

      <!-- Formação -->
      <section class="bg-white rounded-lg shadow p-6">
        <h3 class="text-xl font-bold text-sky-700 mb-3">Formação</h3>
        <ul class="text-gray-700 space-y-3">
          <li>
            <span class="font-semibold">Ensino Médio - Interação</span><br>
            <span class="text-sm text-gray-500">01/2017 - 11/2023</span>
          </li>
          <li>
            <span class="font-semibold">Ensino Superior - Unimar</span><br>
            <span class="text-sm text-gray-500">01/2024 - 12/2026</span>
          </li>
        </ul>
      </section>

      <!-- Cursos -->
      <section class="bg-white rounded-lg shadow p-6">
        <h3 class="text-xl font-bold text-sky-700 mb-3">Cursos</h3>
        <ul class="text-gray-700 space-y-3">
          <li>
            <span class="font-semibold">Bootcamp Jovem Programador - Unimar</span><br>
            <span class="text-sm text-gray-500">08/2024 - 09/2024</span>
          </li>
          <li>
            <span class="font-semibold">Programação em Python no Raspberry - Senai</span><br>
            <span class="text-sm text-gray-500">04/2024 - 05/2024</span>
          </li>
          <li>
            <span class="font-semibold">Implantação de Serviços em Nuvem - Microsoft AZ-900</span><br>
            <span class="text-sm text-gray-500">03/2024 - 04/2024</span>
          </li>
          <li>
            <span class="font-semibold">Jornada Python - Hashtag treinamentos</span><br>
            <span class="text-sm text-gray-500">01/2024 - 01/2024</span>
          </li>
          <li>
            <span class="font-semibold">Semana do Excel - Hashtag treinamentos</span><br>
            <span class="text-sm text-gray-500">01/2024 - 01/2024</span>
          </li>
        </ul>
      </section>
    </main>
  </div>
</template>