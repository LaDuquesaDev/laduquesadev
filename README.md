<h2 align="center">Hi 👋, my name is Yulimar, but everyone calls me Yuli (or sometimes Duquesa)</h2>
<h3 align="center">Frontend & Mobile Developer | DevRel</h3>
<p align="center">
  <strong>Creating impactful software with a passion for clean code and great UX</strong>
</p>

## Who I am?

```javascript
"use client"

import React from "react"
import { PersonalIntroductionSection } from "@/styles/personal-introduction-styles"

interface PersonalInfo {
  nombre: string
  rol: string
  tecnologias: string[]
  aprendiendo: string
  ubicacion: string
  objetivos: string[]
}

const crearPresentacionPersonal = (info: PersonalInfo): string => {
  return `👷 ${info.nombre} - ${info.rol}
💡 Stack Tecnológico: ${info.tecnologias.join(", ")}
📚 Aprendiendo: ${info.aprendiendo}
📍 Ubicación: ${info.ubicacion}
🎯 Objetivos: ${info.objetivos.join(" | ")}`
}

export const PersonalIntroduction = () => {
  const presentacion = crearPresentacionPersonal({
    nombre: "Yulimar Duque de Alba",
    rol: "Frontend & Mobile Developer",
    tecnologias: ["TypeScript", "React", "React Native", "Next.js", "Tailwind CSS"],
    aprendiendo: "AI & Machine Learning",
    ubicacion: "Medellín",
    objetivos: ["Construir proyectos impactantes", "Mantenerse saludable", "Disfrutar del proceso"]
  })

  return <PersonalIntroductionSection>{presentacion}</PersonalIntroductionSection>
}
```

![YouTube Channel Subscribers](https://img.shields.io/youtube/channel/subscribers/UC9iZHV96PZ6-7IzuT5eEMtg)
![YouTube Channel Views](https://img.shields.io/youtube/channel/views/UC9iZHV96PZ6-7IzuT5eEMtg)
![GitHub followers](https://img.shields.io/github/followers/laduquesadev?style=social)
![GitHub User's stars](https://img.shields.io/github/stars/laduquesadev)
<br></br>

## Languages and Tools
<p align="left"> 
  <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/1150px-React-icon.svg.png" alt="react" width="40" height="40"/></a> 
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/></a> 
  <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/></a> 
  <a href="https://redux.js.org/" target="_blank" rel="noreferrer"> <img src="https://redux.js.org/img/redux.svg" alt="redux" width="40" height="40"/></a> 
  <a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/></a> 
  <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/></a> 
  <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/></a> 
  <a href="https://es.wikipedia.org/wiki/CSS" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/d/d5/CSS3_logo_and_wordmark.svg" alt="css" width="40" height="40"/></a>
  <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/></a>
</p>
<br></br>

## 🚀 Featured Projects

### ✒️ [La Duquesa Portfolio](https://laduquesadev-portfolio.vercel.app/)
**Stack:** JavaScript, Astro, Tailwind CSS  
📦 [Source code](https://github.com/LaDuquesaDev/laduquesadev-portfolio)  
Portfolio where I showcase my projects, skills, and passion for creating beautiful and functional web experiences.

---

### ✒️ [La Duquesa Blog](https://laduquesa-blog.vercel.app/)  
**Stack:** Astro, TypeScript, Tailwind CSS  
📦 [Source code](https://github.com/LaDuquesaDev/laduquesa-blog)  
Personal blog where I share articles related to technology and lifestyle as a software engineer.

---

### 🐶 [Pop Corner](https://github.com/LaDuquesaDev/popcorner)  
**Stack:** React Native, TypeScript, Zustand, TanStack Query  
📦 [Source code](https://github.com/LaDuquesaDev/popcorner)  
A mobile experience for movie lovers who want to explore films, discover details, and create their own watchlist.

---

### 🔗 [Chatbot App](https://github.com/LaDuquesaDev/chatbot_app)
**Stack:** React Native, Expo  
📦 [Source code](https://github.com/LaDuquesaDev/chatbot_app)  
Chatbot trained to answer questions about the user's credit history.
<br></br>

## Connect with me
<p align="left">
  <a href="https://linkedin.com/in/laduquesadev"><img alt="Linkedin" title="Yulimar Duque Linkedin" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://www.youtube.com/@laduquesadev"><img alt="Youtube" title="LaDuquesaDev Youtube" src="https://img.shields.io/badge/Youtube-D14836?style=for-the-badge&logo=youtube&logoColor=white"></a>
  <a href="https://instagram.com/laduquesadev/"><img alt="Instagram" title="LaDuquesaDev Instagram" src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a>
</p>
<br></br>

### ⚙️ &nbsp;GitHub Analytics
<p align="center">
<a href="https://github.com/LaDuquesaDev">
  <img height="160em" src="https://github-readme-stats-eight-theta.vercel.app/api?username=LaDuquesaDev&show_icons=true&theme=algolia&include_all_commits=true&count_private=true"/>
  <img height="160em" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=LaDuquesaDev&layout=compact&langs_count=8&theme=algolia"/>
</a>
</p>
