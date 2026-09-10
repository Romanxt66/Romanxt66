<h1 align="center">¡Hola! 👋 Soy Roman</h1>

<p align="center">
  Desarrollador en formación (SENA) 🇨🇴 · Aplicaciones web full-stack, bases de datos y despliegue con Docker.
</p>

<p align="center">
  <a href="https://github.com/Romanxt66?tab=repositories">
    <img src="https://img.shields.io/badge/Repositorios-Ver%20todos-1f6feb?style=for-the-badge&logo=github&logoColor=white" alt="Repositorios" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=Romanxt66&style=for-the-badge&color=1f6feb&label=Visitas+al+perfil" alt="Visitas al perfil" />
</p>

---

## 🚀 Sobre mí

- 🔭 Actualmente trabajo en el **Sistema de Gestión de Prácticas del SENA**, que llevé de una app monolítica en Flask a una arquitectura **Spring Boot 3 + React** compartiendo la misma base de datos PostgreSQL.
- 🌱 Aprendiendo **Next.js 16, TypeScript y Prisma** construyendo *Lab*, un panel interno propio.
- 🧰 Me gusta que las cosas **corran de verdad**: cada proyecto sale con su `Dockerfile`, su `docker-compose.yml` y su despliegue en Coolify.
- 📚 También documento: manuales de usuario por rol, guías de despliegue y notas de arquitectura dentro de cada repo.
- 📫 Escríbeme: [nicolastorresrr@gmail.com](mailto:nicolastorresrr@gmail.com)

---

## 🛠️ Tecnologías que uso

**Lenguajes**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Backend**

![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot%203-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![Hibernate](https://img.shields.io/badge/JPA%20%2F%20Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Jinja](https://img.shields.io/badge/Jinja2-B41717?style=flat-square&logo=jinja&logoColor=white)

**Datos e infraestructura**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Coolify](https://img.shields.io/badge/Coolify-8B5CF6?style=flat-square&logo=coolify&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 📌 Proyectos destacados

### 🎓 Sistema de Gestión de Prácticas SENA

Plataforma para administrar la etapa productiva de los aprendices: fichas, instructores, empresas, evidencias y progreso. Empezó en Flask y hoy tiene además un backend y un frontend independientes sobre **la misma base de datos**.

| Repositorio | Qué es | Stack |
|---|---|---|
| [**Gestion_De_Practicas_SENA**](https://github.com/Romanxt66/Gestion_De_Practicas_SENA) | App original monolítica: roles admin/instructor/aprendiz, evidencias, exportación a Excel y manuales de usuario | Flask 3 · SQLAlchemy · Flask-Migrate · PostgreSQL · Docker |
| [**Practicas_Sistema_Spring_Back**](https://github.com/Romanxt66/Practicas_Sistema_Spring_Back) | API REST que convive con Flask sin tocar el esquema (`ddl-auto=none`, hashes compatibles con Werkzeug) | Spring Boot 3 · JPA · JWT · PostgreSQL |
| [**Practicas_Sistema_Spring_Front**](https://github.com/Romanxt66/Practicas_Sistema_Spring_Front) | SPA con los tres paneles completos, rutas protegidas por rol y sesión JWT en `localStorage` | React · Vite · Axios · Nginx |

### 🧪 [Lab](https://github.com/Romanxt66/Lab)

Panel interno todo-en-uno: automatizaciones programadas, plantillas de correo, finanzas, inventario, monitoreo de uptime e integraciones con GitHub, Coolify y n8n.
`Next.js 16` · `TypeScript` · `Prisma 7` · `PostgreSQL` · `Tailwind CSS` · `Vitest`

### 📚 [Biblioteca-Flask22](https://github.com/Romanxt66/Biblioteca-Flask22)

Sistema de gestión de biblioteca con autenticación, préstamos y **generación de códigos QR** para los ejemplares.
`Flask` · `Flask-Login` · `SQLAlchemy` · `qrcode` · `Pillow`

### 🛒 [POS](https://github.com/Romanxt66/POS)

Punto de venta de escritorio con interfaz propia en tema oscuro, separando dominio, servicio y GUI. Incluye ejecutable.
`Python` · `Tkinter` · `Arquitectura por capas`

### 🐍 [GUIA1](https://github.com/Romanxt66/GUIA1) · [GUIA2](https://github.com/Romanxt66/GUIA2) · [GUIA3](https://github.com/Romanxt66/GUIA3) · [GUIA4](https://github.com/Romanxt66/GUIA4)

Guías de formación en Python: desde sintaxis y estructuras de control hasta ejercicios más completos.

---

## 📊 Mis estadísticas

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Romanxt66&show_icons=true&hide_border=true&count_private=true&theme=tokyonight" alt="Estadísticas de GitHub de Romanxt66" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Romanxt66&layout=compact&hide_border=true&langs_count=8&theme=tokyonight" alt="Lenguajes más usados" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Romanxt66&hide_border=true&theme=tokyonight" alt="Racha de contribuciones" />
</p>

---

<p align="center">
  <i>⚡ Dato curioso: casi todos mis proyectos comparten la misma base de datos PostgreSQL en Coolify — migrar de framework sin migrar los datos también es un ejercicio de arquitectura.</i>
</p>
