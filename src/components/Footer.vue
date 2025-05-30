<template>
  <footer class="bg-sky-700 text-white py-6 px-8 flex flex-col md:flex-row justify-between items-center gap-4 mt-8 rounded-t-lg shadow-lg">
    <div class="text-center md:text-left mb-2 md:mb-0">
      <span class="font-semibold text-lg">© {{ new Date().getFullYear() }} Matheus Thierry Santos da Silva</span>
      <span class="block text-sm text-sky-100">Aluno de ADS da Unimar</span>
    </div>
    <div class="flex gap-8">
      <a href="https://github.com/Thierry2210" target="_blank" rel="noopener noreferrer"
        @click.prevent="socialAlert('GitHub')" class="flex flex-col items-center hover:text-sky-300 transition">
        <img src="@/assets/img/github.png" alt="GitHub" class="w-8 h-8 mb-1" />
        <span class="text-xs">Github</span>
      </a>
      <a href="https://www.linkedin.com/in/matheus-thierry-4512842b3/" target="_blank" rel="noopener noreferrer"
        @click.prevent="socialAlert('LinkedIn')" class="flex flex-col items-center hover:text-sky-300 transition">
        <img src="@/assets/img/linkedin.png" alt="LinkedIn" class="w-8 h-8 mb-1" />
        <span class="text-xs">Linkedin</span>
      </a>
      <a href="https://www.instagram.com/mthierry_/" target="_blank" rel="noopener noreferrer"
        @click.prevent="socialAlert('Instagram')" class="flex flex-col items-center hover:text-sky-300 transition">
        <img src="@/assets/img/instagram.png" alt="Instagram" class="w-8 h-8 mb-1" />
        <span class="text-xs">Instagram</span>
      </a>
    </div>
  </footer>
</template>

<script setup>
function socialAlert(platform) {
  alert(`Você está sendo redirecionado para o ${platform}.`);
  if (platform === 'GitHub') {
    window.open('https://github.com/Thierry2210', '_blank');
  } else if (platform === 'LinkedIn') {
    window.open('https://www.linkedin.com/in/matheus-thierry-4512842b3/', '_blank');
  } else if (platform === 'Instagram') {
    window.open('https://www.instagram.com/mthierry_/', '_blank');
  }
}
</script>