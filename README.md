### Hi there! <img src="https://emojis.slackmojis.com/emojis/images/1536351075/4594/blob-wave.gif" width="25"/>
### Software Engineering Student | Computer Science & Systems

---

## 🎯 About Me

<div align="center">

\`\`\`javascript
const daniela = {
    location: "Peru 🇵🇪",
    education: "Computer Science & Systems Engineering - UPAO",
    focus: ["Web Development", "Databases"],
    status: "Always learning 📚"
};
\`\`\`

Enhanced animated lunar scene with floating cat and moon 
<div class="lunar-scene">
  <div class="moon">🌕</div>
  <div class="cat">🐈‍⬛</div>
  <div class="stars">✨</div>
  <div class="stars star2">⭐</div>
  <div class="stars star3">💫</div>
  <div class="magic-text">*Programando con magia lunar* ✨</div>
</div>

<style>
.lunar-scene {
  position: relative;
  height: 180px;
  background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
  border-radius: 20px;
  padding: 20px;
  margin: 30px auto;
  max-width: 400px;
  overflow: hidden;
  box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
}

.moon {
  font-size: 3.5em;
  position: absolute;
  right: 30px;
  top: 20px;
  animation: moonFloat 4s ease-in-out infinite;
  filter: drop-shadow(0 0 20px #fef3c7);
}

.cat {
  font-size: 2.5em;
  position: absolute;
  left: 40px;
  bottom: 40px;
  animation: catBounce 2.5s ease-in-out infinite;
  transform-origin: bottom center;
}

.stars {
  font-size: 1.5em;
  position: absolute;
  animation: twinkle 2s ease-in-out infinite;
}

.stars:nth-child(3) {
  top: 30px;
  left: 20%;
  animation-delay: 0s;
}

.star2 {
  top: 50px;
  right: 25%;
  animation-delay: 0.7s;
}

.star3 {
  top: 20px;
  left: 50%;
  animation-delay: 1.4s;
}

.magic-text {
  position: absolute;
  bottom: 10px;
  left: 50%;
  transform: translateX(-50%);
  font-size: 0.9em;
  color: #fef3c7;
  font-style: italic;
  animation: glow 3s ease-in-out infinite;
}

@keyframes moonFloat {
  0%, 100% { 
    transform: translateY(0px) rotate(0deg); 
  }
  25% { 
    transform: translateY(-8px) rotate(2deg); 
  }
  50% { 
    transform: translateY(-15px) rotate(0deg); 
  }
  75% { 
    transform: translateY(-8px) rotate(-2deg); 
  }
}

@keyframes catBounce {
  0%, 100% { 
    transform: translateY(0px) scaleY(1); 
  }
  30% { 
    transform: translateY(-10px) scaleY(1.1); 
  }
  60% { 
    transform: translateY(-5px) scaleY(0.95); 
  }
}

@keyframes twinkle {
  0%, 100% { 
    opacity: 1; 
    transform: scale(1); 
  }
  50% { 
    opacity: 0.3; 
    transform: scale(1.2); 
  }
}

@keyframes glow {
  0%, 100% { 
    text-shadow: 0 0 5px #fef3c7; 
  }
  50% { 
    text-shadow: 0 0 20px #fef3c7, 0 0 30px #f59e0b; 
  }
}
</style>

**Código + Luna = Magia** 🌌

</div>

## 🛠️ Tech Stack

**Languages:**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=java&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)

**Databases:**  
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat&logo=microsoft%20sql%20server&logoColor=white)

## 📊 GitHub Stats

<div align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=Dxnn017&show_icons=true&theme=tokyonight&hide_border=true" />
  <img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Dxnn017&layout=compact&theme=tokyonight&hide_border=true" />
</div>

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/daniela-nieve-64b571261)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dannievi017@gmail.com)

---

*"The future belongs to those who believe in the beauty of their dreams... and code them"* ✨

\`\`\`javascript
const luna = {
    name: "Luna 🐱",
    status: "Floating around the code",
    currentActivity: "Helping debug at 2 AM",
    favoriteSpot: "On my keyboard",
    mood: () => ["😸 Playful", "😴 Sleepy", "🤔 Curious", "😻 Happy"][Math.floor(Math.random() * 4)],
    
    meow: function() {
        return "Meow! Time to code! 🌙✨";
    }
};

// Try this in your console!
console.log(luna.meow());
