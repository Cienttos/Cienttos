<h1 align="center">
  <a href="#">Hi there! I'm <span id="typed"></span> 👋</a>
</h1>

<script>
  const words = ["Facundo Cientofante", "a Full-Stack Developer", "passionate about UI/UX"];
  let i = 0;
  let j = 0;
  let currentWord = "";
  let isDeleting = false;
  
  function type() {
    currentWord = words[i].substring(0, j);
    document.getElementById("typed").textContent = currentWord;
    
    if (!isDeleting && j < words[i].length) {
      j++;
      setTimeout(type, 100);
    } else if (isDeleting && j > 0) {
      j--;
      setTimeout(type, 50);
    } else {
      isDeleting = !isDeleting;
      if (!isDeleting) i = (i + 1) % words.length;
      setTimeout(type, 1000);
    }
  }
  
  document.addEventListener("DOMContentLoaded", type);
</script>

```js
const facundo = {
    fullStackDeveloper: true,
    passion: "UI/UX & modern web experiences",
    alwaysLearning: true
};
```

<p align="center">
  <img src="https://your-image-url.com" alt="Banner" width="100%"/>
</p>

## 🚀 Tech Stack

### 💻 Languages & Frameworks
<p>
  <img src="https://img.shields.io/badge/JavaScript-8B5CF6?style=flat-square&logo=javascript&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-8B5CF6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-8B5CF6?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java-8B5CF6?style=flat-square&logo=java&logoColor=white"/>
  <img src="https://img.shields.io/badge/PHP-8B5CF6?style=flat-square&logo=php&logoColor=white"/>
  <img src="https://img.shields.io/badge/Node.js-8B5CF6?style=flat-square&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-8B5CF6?style=flat-square&logo=react&logoColor=white"/>
  <img src="https://img.shields.io/badge/Astro-8B5CF6?style=flat-square&logo=astro&logoColor=white"/>
  <img src="https://img.shields.io/badge/TailwindCSS-8B5CF6?style=flat-square&logo=tailwind-css&logoColor=white"/>
</p>

### 🎨 UI/UX & Design Tools
<p>
  <img src="https://img.shields.io/badge/Figma-8B5CF6?style=flat-square&logo=figma&logoColor=white"/>
  <img src="https://img.shields.io/badge/Canva-8B5CF6?style=flat-square&logo=canva&logoColor=white"/>
  <img src="https://img.shields.io/badge/SolidEdge-8B5CF6?style=flat-square&logo=siemens&logoColor=white"/>
</p>

## 📊 GitHub Stats
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=FacundoCientofante&show_icons=true&theme=tokyonight"/>
</p>

## 📌 Top Languages
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=FacundoCientofante&layout=compact&theme=tokyonight"/>
</p>

## 🌎 Connect with me
<p>
  <a href="https://www.linkedin.com/in/tu-perfil"><img src="https://img.shields.io/badge/LinkedIn-8B5CF6?style=flat-square&logo=linkedin"/></a>
  <a href="https://twitter.com/tu-usuario"><img src="https://img.shields.io/badge/Twitter-8B5CF6?style=flat-square&logo=twitter&logoColor=white"/></a>
</p>
