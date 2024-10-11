# 👋 Hello, I'm Magnum Johanson de Abreu!

<picture>
  <source
    srcset="https://github-readme-stats.vercel.app/api?username=Magnumja&show_icons=true&theme=radical"
    media="(prefers-color-scheme: dark)"
  />
  <source
    srcset="https://github-readme-stats.vercel.app/api?username=Magnumja&show_icons=true"
    media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
  />
  <img src="https://github-readme-stats.vercel.app/api?username=Magnumja&show_icons=true" />
</picture>

---

## About Me

<h3 align="center">
  <span id="typed"></span>
</h3>

<script>
  const textArray = [
    "Age: 21", 
    "Studying Computer Science at Dom Bosco Catholic University.", 
    "Currently seeking internships.", 
    "Based in Campo Grande, MS, Brazil."
  ];
  let currentIndex = 0;
  let currentText = "";
  let charIndex = 0;

  function type() {
    if (charIndex < textArray[currentIndex].length) {
      currentText += textArray[currentIndex].charAt(charIndex);
      document.getElementById("typed").innerHTML = currentText;
      charIndex++;
      setTimeout(type, 50);  // Velocidade de digitação mais rápida (50ms por caractere)
    } else {
      setTimeout(erase, 2000);  // Pausa de 2 segundos antes de apagar o texto
    }
  }

  function erase() {
    if (charIndex > 0) {
      currentText = textArray[currentIndex].substring(0, charIndex - 1);
      document.getElementById("typed").innerHTML = currentText;
      charIndex--;
      setTimeout(erase, 30);  // Velocidade de apagar (mais rápida, 30ms)
    } else {
      currentIndex = (currentIndex + 1) % textArray.length;  // Passa para o próximo texto
      setTimeout(type, 500);  // Pausa de 0,5 segundos antes de começar a digitar o próximo
    }
  }

  document.addEventListener("DOMContentLoaded", function() {
    setTimeout(type, 500);  // Começa a digitar após 0,5 segundos
  });
</script>


### Languages

-  **Python**
-  **C**



<div style="display: inline_block; border: 2px solid #3498db; border-radius: 15px; padding: 10px; background-color: #ecf0f1;">
  <img align="center" alt="Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
</div>

---

## Connect with Me

<div> 
  <a href="https://www.instagram.com/magnum.abreu/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/magnumdeabreu/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
</div>
