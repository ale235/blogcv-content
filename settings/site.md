---
site_name: "Tu Nombre | Portfolio & Blog"
site_url: "https://tusitio.com"
author: "Tu Nombre Completo"
copyright: "© 2024 Tu Nombre. Todos los derechos reservados."
favicon: "https://tusitio.com/favicon.ico"
logo: "https://tusitio.com/logo.png"
logo_alt: "Logo de Tu Nombre"

# SEO
default_meta_description: "Portfolio y Blog de Tu Nombre - Desarrollador Full Stack especializado en Laravel, Vue.js y PHP. Proyectos, artículos y más."
default_meta_keywords: "desarrollador, full stack, laravel, vue.js, php, portfolio, blog, web developer, backend, frontend"
default_og_image: "https://tusitio.com/og-image.jpg"
default_og_type: "website"

# Twitter Card
twitter_card_type: "summary_large_image"
twitter_creator: "@tu_usuario"
twitter_site: "@tu_usuario"

# Social Links
social:
  github: 
    url: "https://github.com/tu-usuario"
    username: "tu-usuario"
    enabled: true
  linkedin: 
    url: "https://linkedin.com/in/tu-usuario"
    username: "tu-usuario"
    enabled: true
  twitter: 
    url: "https://twitter.com/tu_usuario"
    username: "@tu_usuario"
    enabled: true
  facebook: 
    url: ""
    username: ""
    enabled: false
  instagram: 
    url: "https://instagram.com/tu_usuario"
    username: "tu_usuario"
    enabled: false
  blog: 
    url: "https://tusitio.com/blog"
    enabled: true
  dev_to:
    url: "https://dev.to/tu_usuario"
    username: "tu_usuario"
    enabled: false
  youtube:
    url: ""
    username: ""
    enabled: false

# Contact
contact_email: "hola@tusitio.com"
contact_form_enabled: true
contact_email_visible: true

# reCAPTCHA (opcional - para formulario de contacto)
recaptcha_enabled: true
recaptcha_site_key: "tu-recaptcha-site-key-aqui"

# Analytics
google_analytics_id: "G-XXXXXXXXXX"
google_analytics_enabled: false
google_tag_manager_id: "GTM-XXXXXXX"
google_tag_manager_enabled: false

# Features / Funcionalidades
features:
  blog_enabled: true
  portfolio_enabled: true
  resume_enabled: true
  resume_download: true
  resume_pdf_url: "https://tusitio.com/files/cv-tu-nombre.pdf"
  contact_form: true
  comments_enabled: false
  newsletter_enabled: false
  search_enabled: false
  dark_mode_toggle: true
  language_switcher: true

# Blog Configuration
blog:
  posts_per_page: 10
  show_author: true
  show_date: true
  show_reading_time: true
  show_tags: true
  show_category: true
  enable_sharing: true
  related_posts: 3

# Comments (si lo habilitas)
comments:
  provider: "disqus"  # disqus, facebook, none
  disqus_shortname: "tu-sitio"

# Newsletter (si lo habilitas)
newsletter:
  provider: "mailchimp"  # mailchimp, convertkit, none
  mailchimp_action_url: "https://XXXXX.us1.list-manage.com/subscribe/post?u=XXXXX&id=XXXXX"

# Theme Colors
theme:
  primary_color: "#3490dc"
  secondary_color: "#6574cd"
  accent_color: "#f6993f"
  success_color: "#38c172"
  error_color: "#e3342f"
  warning_color: "#ffed4e"
  info_color: "#6cb2eb"
  dark_mode_enabled: true

# Navigation Menu
navigation:
  - name: "Inicio"
    url: "/"
    icon: "home"
    enabled: true
  - name: "Blog"
    url: "/blog"
    icon: "book"
    enabled: true
  - name: "CV"
    url: "/resume"
    icon: "briefcase"
    enabled: true
  - name: "Habilidades"
    url: "/skills"
    icon: "code"
    enabled: true
  - name: "Sobre Mí"
    url: "/aboutme"
    icon: "user"
    enabled: true
  - name: "Contacto"
    url: "/contactme"
    icon: "mail"
    enabled: true

# Footer Links
footer:
  show_social: true
  show_copyright: true
  show_credits: true
  credits_text: "Hecho con ❤️ y Laravel"
  links:
    - name: "Privacidad"
      url: "/privacy"
      enabled: false
    - name: "Términos"
      url: "/terms"
      enabled: false
    - name: "Sitemap"
      url: "/sitemap.xml"
      enabled: false

# API Endpoints (para futuras integraciones)
api:
  github_repo: "tu-usuario/blogcv-content"
  github_branch: "main"
  cache_duration: 3600  # 1 hora en segundos

# Performance
performance:
  lazy_load_images: true
  minify_html: true
  enable_caching: true
  cache_ttl: 3600

# Security
security:
  enable_csrf: true
  enable_cors: false
  allowed_origins: []

# Locale / Internationalization
locale:
  default: "es"
  available:
    - code: "es"
      name: "Español"
      flag: "🇪🇸"
      enabled: true
    - code: "en"
      name: "English"
      flag: "🇬🇧"
      enabled: false

# Date Format
date_format: "d/m/Y"
datetime_format: "d/m/Y H:i"
timezone: "America/Argentina/Buenos_Aires"

# Misc
misc:
  maintenance_mode: false
  under_construction: false
  show_version: false
  version: "2.0.0"
---

# Configuraciones del Sitio

Este archivo contiene todas las configuraciones globales del sitio web.

## Cómo Usar

Las configuraciones en el front matter YAML de este archivo se cargan automáticamente y están disponibles en toda la aplicación.

## Estructura

- **SEO**: Meta tags por defecto para todas las páginas
- **Social**: Links a redes sociales y perfiles
- **Contact**: Información de contacto y formularios
- **Features**: Funcionalidades activadas/desactivadas
- **Theme**: Colores y configuración visual
- **Navigation**: Menú principal del sitio
- **Footer**: Configuración del pie de página
- **API**: Configuraciones para APIs externas
- **Performance**: Optimizaciones de rendimiento
- **Security**: Configuraciones de seguridad
- **Locale**: Idiomas y localización

## Actualización

Para actualizar cualquier configuración:

1. Edita este archivo
2. Commit y push a GitHub
3. La aplicación leerá los nuevos valores (según el caché configurado)

## Notas

- Los valores de `recaptcha_site_key`, `google_analytics_id`, etc. deben configurarse en el `.env` de la aplicación por seguridad
- Este archivo contiene solo las configuraciones "públicas"
- Las configuraciones sensibles (API keys, passwords) van en `.env`
---
title: "Sobre Mí"
language: "es"
updated_at: "2024-10-10"
meta_description: "Conoce más sobre [Tu Nombre] - Desarrollador Full Stack"
---

# Sobre Mí 👨‍💻

¡Hola! Soy **[Tu Nombre]**, un desarrollador full stack apasionado por crear soluciones web elegantes y escalables.

## Mi Historia

Mi viaje en el desarrollo web comenzó en **20XX**, cuando [cuenta cómo empezaste en el mundo de la programación]. Desde entonces, he trabajado en proyectos que van desde pequeñas startups hasta aplicaciones empresariales con miles de usuarios.

Lo que más me apasiona del desarrollo es **resolver problemas complejos con código simple**. Creo firmemente que el mejor código es aquel que otro developer puede entender fácilmente seis meses después.

## ¿Qué Hago?

Actualmente trabajo como **[Tu Posición Actual]** en **[Empresa o Freelance]**, donde:

- 🚀 Desarrollo aplicaciones web con Laravel y Vue.js
- 🏗️ Diseño arquitecturas escalables y mantenibles
- 👥 Colaboro con equipos multidisciplinarios
- 📝 Escribo código limpio y testeado
- 🎓 Aprendo constantemente nuevas tecnologías

## Mi Enfoque de Trabajo

### 🎯 Primero el Usuario

Siempre pienso en el usuario final. Una aplicación puede tener el código más elegante del mundo, pero si no resuelve un problema real del usuario, no sirve.

### 🧪 Testing es Amor

No confío en código sin tests. Los tests no solo previenen bugs, sino que también documentan cómo debe funcionar el código y dan confianza para refactorizar.

### 📚 Código Legible

Escribo código pensando en que otro developer (o yo en 6 meses) tendrá que mantenerlo. Prefiero claridad sobre "inteligencia".

### 🔄 Mejora Continua

Cada proyecto es una oportunidad para aprender algo nuevo. Hago retrospectivas personales para identificar qué puedo mejorar.

## Filosofía de Desarrollo

Sigo estos principios en mi día a día:

1. **KISS** (Keep It Simple, Stupid): La simplicidad es sofisticación
2. **DRY** (Don't Repeat Yourself): Si lo escribiste dos veces, abstráelo
3. **YAGNI** (You Aren't Gonna Need It): No implementes features que "tal vez" necesites
4. **SOLID**: Principios para código orientado a objetos mantenible
5. **Clean Code**: El código se lee más veces de las que se escribe

## Stack Preferido

Mi combinación favorita de tecnologías (TALL Stack + extras):

```
Backend:  Laravel + PHP 8.2
Frontend: Vue.js 3 + Tailwind CSS
DB:       MySQL + Redis
DevOps:   Docker + GitHub Actions
Testing:  PHPUnit + Jest
```

Aunque soy flexible y me adapto al stack del proyecto. Al final, las herramientas son solo medios para resolver problemas.

## Más Allá del Código

Cuando no estoy programando, puedes encontrarme:

- 📚 **Leyendo**: Tanto libros técnicos como ciencia ficción
- 🎮 **Jugando**: Videojuegos (principalmente [género que te guste])
- 🏃 **Haciendo deporte**: [Tu deporte/actividad]
- ☕ **Tomando café**: Soy un coffee enthusiast
- 🎵 **Escuchando música**: Programo mejor con [tipo de música]
- 🌍 **Viajando**: Cuando puedo, me encanta conocer nuevos lugares
- 🎬 **Viendo series**: Fan de [series que te gusten]

## Valores Profesionales

### 🤝 Colaboración

Creo que los mejores proyectos se construyen en equipo. Me encanta hacer pair programming y participar en code reviews constructivos.

### 💬 Comunicación

La comunicación clara es tan importante como el código limpio. Si algo no está claro, prefiero preguntar antes que asumir.

### 🎓 Aprendizaje

La tecnología cambia constantemente. Dedico tiempo cada semana a aprender algo nuevo, ya sea un framework, un patrón de diseño o mejores prácticas.

### 🌱 Crecimiento

Siempre busco feedback para mejorar. Los errores son oportunidades de aprendizaje, no fracasos.

## Contribuciones a la Comunidad

Creo en devolver a la comunidad que tanto me ha enseñado:

- 📝 **Escribo en mi blog** sobre lo que aprendo
- 🌟 **Contribuyo a open source** cuando puedo
- 🤝 **Ayudo en Stack Overflow** y foros de Laravel
- 💬 **Participo en comunidades** de developers
- 🎤 **Comparto conocimiento** en meetups (virtual/presencial)

## Mi Setup

Para los curiosos, aquí está mi setup actual:

- 💻 **Laptop**: [Tu laptop]
- ⌨️ **Teclado**: [Tu teclado]
- 🖱️ **Mouse**: [Tu mouse]
- 🖥️ **Monitor**: [Tu monitor]
- 🎧 **Audífonos**: [Tus audífonos]
- 🪑 **Silla**: [Tu silla] (la ergonomía es importante!)
- 💡 **Editor**: VS Code con tema [tu tema]
- 🎨 **Terminal**: [Tu terminal] con [tu shell]

## Proyectos Personales

Siempre tengo algún proyecto personal en marcha:

### 🔧 [Nombre del Proyecto]

[Descripción breve del proyecto, qué problema resuelve, tecnologías usadas]

🔗 [GitHub](https://github.com/tu-usuario/proyecto) | [Demo](https://proyecto.com)

### 🔧 [Otro Proyecto]

[Descripción breve]

🔗 [GitHub](https://github.com/tu-usuario/proyecto2)

## Datos Curiosos

- 🎂 Mi primer "Hola Mundo" fue en [lenguaje] en [año]
- 🐛 Mi bug más memorable fue [anécdota divertida]
- ☕ Promedio de tazas de café al día: [número]
- 🌙 Soy más productivo [de día/de noche]
- 🎵 No puedo programar sin [música/silencio]
- 📚 Mi libro de programación favorito: [libro]

## Let's Connect!

Me encanta conectar con otros developers y hablar sobre tecnología, proyectos o simplemente tomar un café virtual.

📧 **Email**: [tu@email.com]  
💼 **LinkedIn**: [linkedin.com/in/tu-perfil](https://linkedin.com/in/tu-perfil)  
🐦 **Twitter**: [@tu_usuario](https://twitter.com/tu_usuario)  
🐙 **GitHub**: [github.com/tu-usuario](https://github.com/tu-usuario)  
📝 **Blog**: [tublog.com](https://tublog.com)

---

## ¿Trabajamos Juntos?

Si tienes un proyecto en mente o simplemente quieres charlar sobre tecnología:

👉 **[Contáctame](/contactme)**

---

*"El código limpio no se escribe siguiendo un conjunto de reglas. No puedes convertirte en un artesano del software aprendiendo una lista de heurísticas. El profesionalismo y la artesanía provienen de valores que impulsan las disciplinas."* - Robert C. Martin (Uncle Bob)
---
title: "Habilidades Técnicas"
language: "es"
updated_at: "2024-10-10"
---

## 💻 Backend Development

### PHP & Laravel
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)

**Experiencia:** X años  
**Nivel:** Experto ⭐⭐⭐⭐⭐

- Laravel 5.x - 10.x
- APIs RESTful
- Queue Jobs & Scheduling
- Broadcasting & WebSockets
- Testing con PHPUnit
- Eloquent ORM avanzado
- Service Providers & Facades
- Middleware personalizado
- Packages: Passport, Sanctum, Horizon, Telescope

---

### Node.js
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)

**Experiencia:** X años  
**Nivel:** Intermedio/Avanzado ⭐⭐⭐⭐

- Express.js
- APIs REST
- MongoDB con Mongoose
- Socket.io para real-time
- NPM scripts y automatización

---

## 🎨 Frontend Development

### Vue.js
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)

**Experiencia:** X años  
**Nivel:** Avanzado ⭐⭐⭐⭐⭐

- Vue 2 & Vue 3
- Composition API
- Vuex / Pinia para state management
- Vue Router
- Vuetify, Quasar, Element UI
- Testing con Jest y Vue Test Utils

---

### JavaScript Moderno
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Experiencia:** X años  
**Nivel:** Avanzado ⭐⭐⭐⭐

- ES6+ (arrow functions, destructuring, spread/rest)
- Async/Await y Promises
- Fetch API y Axios
- Modules (import/export)
- Event Loop y asincronía
- Closures y scope

---

### HTML & CSS
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Experiencia:** X años  
**Nivel:** Avanzado ⭐⭐⭐⭐

- Semantic HTML5
- CSS Grid & Flexbox
- Responsive Design (Mobile First)
- Sass/SCSS
- Tailwind CSS
- Bootstrap 4/5
- Animaciones CSS

---

### Alpine.js & Livewire
![Alpine.js](https://img.shields.io/badge/Alpine.js-8BC0D0?style=for-the-badge&logo=alpine.js&logoColor=black)

**Experiencia:** X años  
**Nivel:** Intermedio ⭐⭐⭐

- Alpine.js para interactividad
- Laravel Livewire components
- TALL Stack (Tailwind, Alpine, Laravel, Livewire)

---

## 🗄️ Bases de Datos

### MySQL
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**Experiencia:** X años  
**Nivel:** Avanzado ⭐⭐⭐⭐⭐

- Diseño de schemas normalizados
- Queries complejas (JOINs, subqueries, CTEs)
- Optimización de queries (EXPLAIN, índices)
- Stored procedures y triggers
- Views y materialized views
- Replicación básica
- Backup y restore

---

### Redis
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**Experiencia:** X años  
**Nivel:** Intermedio ⭐⭐⭐⭐

- Caché de datos y queries
- Session storage
- Queue backend para Laravel
- Pub/Sub básico
- Estructuras de datos (strings, hashes, lists, sets)

---

### PostgreSQL
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

**Experiencia:** X años  
**Nivel:** Básico/Intermedio ⭐⭐⭐

- Queries básicas y avanzadas
- JSON fields (JSONB)
- Full-text search
- Índices y performance tuning

---

### MongoDB
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

**Experiencia:** X años  
**Nivel:** Básico ⭐⭐

- CRUD operations
- Mongoose ODM
- Aggregation pipeline básico

---

## 🛠️ DevOps & Tools

### Docker
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**Experiencia:** X años  
**Nivel:** Intermedio ⭐⭐⭐⭐

- Contenedores Docker
- Docker Compose
- Multi-stage builds
- Dockerfiles optimizados
- Docker en desarrollo local
- Docker networks y volumes

---

### Git & GitHub
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

**Experiencia:** X años  
**Nivel:** Avanzado ⭐⭐⭐⭐⭐

- Git flow y GitHub flow
- Branching strategies
- Pull requests y code reviews
- Resolución de conflictos
- GitHub Actions (CI/CD)
- Git hooks
- Rebase, cherry-pick, stash

---

### AWS
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

**Experiencia:** X años  
**Nivel:** Básico-Intermedio ⭐⭐⭐

- EC2 instances
- S3 storage
- RDS databases
- CloudFront CDN
- Route 53
- Lambda básico
- IAM básico

---

### Linux & Terminal
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Experiencia:** X años  
**Nivel:** Intermedio ⭐⭐⭐⭐

- Comandos básicos y avanzados
- Bash scripting
- SSH y manejo de servidores
- Nginx y Apache
- Cron jobs
- Permisos y usuarios

---

## 🧪 Testing & Quality

### PHPUnit
![PHPUnit](https://img.shields.io/badge/PHPUnit-3C9CD7?style=for-the-badge)

**Experiencia:** X años  
**Nivel:** Avanzado ⭐⭐⭐⭐

- Unit tests
- Feature tests
- Mocking & Stubbing
- Test-Driven Development (TDD)
- Code coverage reports

---

### Jest & Testing Library
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)

**Experiencia:** X años  
**Nivel:** Intermedio ⭐⭐⭐

- Unit tests para Vue.js
- Component testing
- Snapshot testing
- Mocking de APIs

---

### PHP CodeSniffer & PHPStan

**Experiencia:** X años  
**Nivel:** Intermedio ⭐⭐⭐

- PSR-12 coding standards
- Static analysis con PHPStan
- Code quality automation

---

## 📦 Package Managers & Build Tools

### Composer & NPM
![Composer](https://img.shields.io/badge/Composer-885630?style=for-the-badge&logo=composer&logoColor=white)
![NPM](https://img.shields.io/badge/NPM-CB3837?style=for-the-badge&logo=npm&logoColor=white)

- Gestión de dependencias PHP
- Gestión de dependencias JavaScript
- Scripts personalizados
- Semantic versioning

---

### Webpack & Vite
![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=for-the-badge&logo=webpack&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

- Bundling de assets
- Hot Module Replacement
- Optimización de builds
- Laravel Mix

---

## 🔧 Other Tools & Services

- **Postman / Insomnia**: Testing de APIs
- **VS Code**: Editor principal
- **PHPStorm**: IDE alternativo
- **Figma**: Colaboración con diseño
- **Jira / Trello**: Project management
- **Slack / Discord**: Comunicación de equipo
- **Notion**: Documentación

---

## 📚 Metodologías & Principios

### Metodologías Ágiles
- ✅ Scrum (Daily standups, sprints, retrospectives)
- ✅ Kanban
- ✅ Extreme Programming (XP) basics

### Principios de Diseño
- ✅ SOLID principles
- ✅ DRY (Don't Repeat Yourself)
- ✅ KISS (Keep It Simple, Stupid)
- ✅ YAGNI (You Aren't Gonna Need It)
- ✅ Clean Code principles
- ✅ Design Patterns (Factory, Repository, Observer, Strategy, etc.)
- ✅ Domain-Driven Design (DDD) basics

### Arquitecturas
- ✅ MVC (Model-View-Controller)
- ✅ Repository Pattern
- ✅ Service Layer Pattern
- ✅ RESTful API design
- ✅ Microservices basics
- ✅ Event-Driven Architecture basics

---

## 💬 Soft Skills

- 👥 **Trabajo en equipo remoto**: Experiencia en equipos distribuidos
- 🗣️ **Comunicación clara**: Explicar conceptos técnicos a no técnicos
- 📝 **Documentación técnica**: Escribir docs claras y útiles
- 🎯 **Resolución de problemas**: Debugging y troubleshooting
- ⏰ **Gestión del tiempo**: Manejo de múltiples tareas y deadlines
- 🧠 **Aprendizaje continuo**: Siempre aprendiendo nuevas tecnologías
- 👨‍🏫 **Mentoring**: Ayudar a juniors a crecer
- 🤝 **Colaboración**: Code reviews constructivos

---

## 🌐 Idiomas

- 🇪🇸 **Español**: Nativo
- 🇬🇧 **Inglés**: Avanzado (C1) - Leo documentación técnica, escribo y hablo fluido
- 🇧🇷 **Português**: Básico/Intermedio (A2/B1) - Comprensión lectora y conversación básica

---

## 📈 Actualmente Aprendiendo

- 🦀 Rust programming language
- ☸️ Kubernetes para orquestación de contenedores
- 🎯 Go (Golang) para microservicios
- 🤖 Machine Learning basics con Python
- 📱 React Native para apps móviles
- 🔐 Web3 & Blockchain basics

---

## 🏆 Intereses Técnicos

- Clean Architecture
- Performance Optimization
- Security Best Practices
- Scalable Systems Design
- Open Source Contribution
- Technical Writing
---
title: "Experiencia Laboral"
category: "experience"
language: "es"
updated_at: "2024-10-10"
---

## [Empresa Actual] - Senior Full Stack Developer

📅 **Período:** Enero 20XX - Presente (X años, X meses)  
📍 **Ubicación:** Remoto / Tu Ciudad, Tu País  
🏢 **Empresa:** [Nombre de la Empresa]  
🔗 **Web:** [empresa.com](https://empresa.com)  
🏭 **Industria:** Tecnología / SaaS / E-commerce / Fintech

### Descripción

Desarrollo y mantenimiento de aplicaciones web empresariales para clientes de [región/país]. Trabajo en equipo distribuido usando metodologías ágiles (Scrum).

### Responsabilidades

- 🚀 Desarrollo de aplicaciones con **Laravel 9/10** y **Vue.js 3**
- 🏗️ Diseño de arquitecturas de software escalables
- 👥 Liderazgo técnico de equipo de X developers
- 📊 Code reviews y mentoring de developers junior
- 🔧 Implementación de CI/CD con GitHub Actions
- 📝 Documentación técnica y de APIs REST
- 🐛 Debugging y optimización de performance
- 💬 Comunicación directa con clientes y stakeholders

### Logros Destacados

- ✅ Reducción del **40%** en tiempo de respuesta de APIs
- ✅ Implementación de suite de tests con **85% de cobertura**
- ✅ Migración exitosa de PHP 7.4 a PHP 8.2
- ✅ Reducción de **30%** en costos de infraestructura con optimizaciones
- ✅ Implementación de sistema de caché que mejoró performance en **60%**
- ✅ Desarrollo de feature que generó **+$XXk** en revenue

### Tecnologías Utilizadas

`Laravel` `Vue.js` `MySQL` `Redis` `Docker` `AWS` `GitHub Actions` `PHPUnit` `Jest` `Tailwind CSS` `Livewire` `API REST` `WebSockets`

---

## [Empresa Anterior] - Backend Developer

📅 **Período:** Junio 20XX - Diciembre 20XX (X años, X meses)  
📍 **Ubicación:** Tu Ciudad, Tu País  
🏢 **Empresa:** [Nombre de la Empresa]  
🏭 **Industria:** Digital Agency / Software House

### Descripción

Desarrollo de APIs REST y aplicaciones web para clientes del sector [sectores donde trabajaste]. Colaboración con equipos de diseño y frontend.

### Responsabilidades

- 🔌 Desarrollo de APIs RESTful con Laravel
- 🔗 Integración con servicios externos (pagos, emails, storage)
- 🗄️ Diseño y optimización de bases de datos MySQL
- 🐛 Debugging y resolución de issues en producción
- 📱 Colaboración con equipo frontend (React/Vue)
- 🧪 Implementación de tests unitarios y de integración

### Logros Destacados

- ✅ Desarrollo de API usada por **+50,000 usuarios**
- ✅ Integración de pasarela de pagos procesando **$XXk mensual**
- ✅ Implementación de sistema de notificaciones real-time
- ✅ Creación de dashboard administrativo con métricas en tiempo real
- ✅ Reducción de bugs en producción en un **70%**

### Tecnologías Utilizadas

`Laravel` `PHP 7.4` `MySQL` `Redis` `Pusher` `Stripe API` `MercadoPago` `Vue.js` `Bootstrap` `jQuery` `Git` `Linux`

---

## [Primera Empresa] - Junior Web Developer

📅 **Período:** Marzo 20XX - Mayo 20XX (X año, X meses)  
📍 **Ubicación:** Tu Ciudad, Tu País  
🏢 **Empresa:** [Nombre de la Empresa]

### Descripción

Primer trabajo como developer profesional. Desarrollo de funcionalidades para [tipo de proyecto/producto]. Aprendizaje acelerado de tecnologías y mejores prácticas.

### Responsabilidades

- 💻 Desarrollo de features con Laravel 5.8
- 🎨 Maquetado de vistas con Blade y Bootstrap
- 🐛 Corrección de bugs reportados por QA
- 📊 Queries SQL y optimización básica
- 📝 Documentación de código y funcionalidades
- 🔄 Participación en dailies y retrospectivas

### Logros Destacados

- ✅ Desarrollo de módulo de reportes usado diariamente
- ✅ Aprendizaje rápido del stack tecnológico
- ✅ Contribución a **+100 commits** en el primer año
- ✅ Implementación de mi primera API REST completa

### Tecnologías Utilizadas

`Laravel 5.8` `PHP 7.2` `MySQL` `jQuery` `Bootstrap 4` `Git` `Apache`

---

## Freelance - Web Developer

📅 **Período:** Enero 20XX - Febrero 20XX (X año)  
📍 **Ubicación:** Remoto  
💼 **Modalidad:** Freelance / Proyectos independientes

### Descripción

Trabajos freelance mientras [terminaba la universidad / comenzaba mi carrera]. Sitios web y aplicaciones para pequeñas empresas y emprendedores.

### Proyectos Destacados

- 🏪 **E-commerce para tienda de [rubro]**
  - Laravel + Vue.js + Stripe
  - Catálogo de productos, carrito, checkout
  - Panel administrativo completo

- 📰 **Blog corporativo con CMS custom**
  - Laravel + Markdown
  - Sistema de posts multiidioma
  - SEO optimizado

- 🏥 **Sistema de turnos para [tipo de negocio]**
  - PHP + MySQL + FullCalendar.js
  - Gestión de citas y notificaciones
  - Dashboard de estadísticas

- 🍕 **Web de restaurant con pedidos online**
  - WordPress customizado
  - Integración con WhatsApp
  - Menú digital responsive

### Tecnologías Utilizadas

`PHP` `Laravel` `WordPress` `MySQL` `HTML/CSS` `JavaScript` `Bootstrap` `jQuery`

---

## Proyectos Open Source / Personales

### [Nombre del Proyecto]

📅 20XX - Presente  
🔗 [GitHub](https://github.com/tu-usuario/proyecto)  
⭐ XXX stars

Descripción breve del proyecto, qué problema resuelve, qué aprendiste, tecnologías usadas.

### [Otro Proyecto]

📅 20XX  
🔗 [GitHub](https://github.com/tu-usuario/proyecto2)

Descripción breve del proyecto.

---

## Referencias

Disponibles a solicitud 📧
---
title: "Educación"
category: "education"
language: "es"
updated_at: "2024-10-10"
---

## Universidad [Tu Universidad]

**Licenciatura en Sistemas / Ingeniería en Sistemas**  
📅 Marzo 20XX - Diciembre 20XX  
📍 Tu Ciudad, Tu País

Tesis: *"[Título de tu tesis si la hiciste]"*  
Promedio: X.X/10

### Materias Destacadas

- Algoritmos y Estructuras de Datos
- Bases de Datos Avanzadas
- Ingeniería de Software
- Arquitectura de Software
- Programación Orientada a Objetos
- Sistemas Operativos
- Redes de Computadoras

### Proyectos Académicos

- **Sistema de gestión [tipo]**: Descripción breve del proyecto y tecnologías usadas
- **Aplicación web [tipo]**: Descripción y stack tecnológico
- **Proyecto final**: Descripción del proyecto de graduación

---

## Instituto Técnico / Secundaria Técnica

**Técnico en Programación / Informática**  
📅 Marzo 20XX - Diciembre 20XX  
📍 Tu Ciudad, Tu País

Proyecto Final: [Descripción breve]

### Tecnologías Aprendidas

- Fundamentos de programación
- Bases de datos relacionales
- Desarrollo web básico
- Metodologías de desarrollo

---

## Cursos y Certificaciones Online

### Laracasts

**Laravel From Scratch**  
📅 20XX  
🎓 Certificado verificable  
🔗 [Ver certificado](#)

Curso completo de Laravel desde los fundamentos hasta conceptos avanzados.

---

### Platzi

**Carrera de Backend con PHP**  
📅 20XX  
🎓 15+ cursos completados  
🔗 [Ver perfil](#)

Cursos incluidos:
- Laravel Avanzado
- API REST con Laravel
- Testing en PHP con PHPUnit
- Docker para Developers
- MySQL y PostgreSQL

---

### Udemy

**[Nombre del curso relevante]**  
📅 20XX  
🎓 40 horas de contenido  
🔗 [Ver certificado](#)

---

### FreeCodeCamp / Otros

**[Certificación relevante]**  
📅 20XX  
🎓 300+ horas  

---

## Educación Continua

Constantemente estoy aprendiendo nuevas tecnologías a través de:

- 📚 **Libros técnicos**: Clean Code, Design Patterns, Domain-Driven Design
- 🎥 **YouTube**: Tutoriales y conferencias técnicas
- 📝 **Blogs técnicos**: Laravel News, PHP.Watch, CSS-Tricks
- 🎓 **Cursos online**: Udemy, Platzi, Laracasts, FreeCodeCamp
- 🤝 **Comunidades**: Stack Overflow, GitHub, foros de Laravel
- 🎤 **Conferencias**: LaraCon, PHP Conference (virtual/presencial)

---

## Idiomas

- 🇪🇸 **Español**: Nativo
- 🇬🇧 **Inglés**: Avanzado - Leo documentación técnica, escribo y converso fluido
- 🇧🇷 **Português**: Básico - Comprensión lectora

---

## Habilidades Blandas Desarrolladas

- 🗣️ Comunicación efectiva
- 👥 Trabajo en equipo
- 🎯 Resolución de problemas
- ⏰ Gestión del tiempo
- 📊 Presentaciones técnicas
- 📝 Documentación técnica
---
title: "10 Tips para Escribir Mejor Código PHP"
slug: "tips-escribir-mejor-codigo-php"
description: "Consejos prácticos para mejorar la calidad de tu código PHP y seguir las mejores prácticas"
summary: "Descubre 10 consejos esenciales que todo desarrollador PHP debería conocer para escribir código más limpio, mantenible y profesional."
published: true
featured: false
language: "es"
image: "https://via.placeholder.com/1200x630"
image_alt: "PHP Code Quality"
created_at: "2024-10-05"
updated_at: "2024-10-05"
reading_time: "6 min"
tags:
  - PHP
  - Clean Code
  - Best Practices
  - Tips
category: "Backend"
author: "Tu Nombre"
---

# 10 Tips para Escribir Mejor Código PHP

Después de años escribiendo PHP, he recopilado estos 10 consejos que considero esenciales para cualquier desarrollador que quiera mejorar la calidad de su código.

## 1. Usa Type Hints (Tipado)

Desde PHP 7.0, podemos declarar tipos para parámetros y valores de retorno:

```php
// ❌ Mal
function calcularTotal($items) {
    // ...
}

// ✅ Bien
function calcularTotal(array $items): float {
    // ...
}
```

## 2. Aprovecha el Null Coalescing Operator

```php
// ❌ Mal
$nombre = isset($_GET['nombre']) ? $_GET['nombre'] : 'Invitado';

// ✅ Bien
$nombre = $_GET['nombre'] ?? 'Invitado';
```

## 3. Usa Strict Types

Activa el modo estricto en tus archivos:

```php
<?php
declare(strict_types=1);

// Ahora PHP será más estricto con los tipos
```

## 4. Evita Else Innecesarios (Early Return)

```php
// ❌ Mal
function esAdulto(int $edad): bool {
    if ($edad >= 18) {
        return true;
    } else {
        return false;
    }
}

// ✅ Bien
function esAdulto(int $edad): bool {
    return $edad >= 18;
}
```

## 5. Usa Constantes de Clase

```php
class OrderStatus {
    public const PENDING = 'pending';
    public const PAID = 'paid';
    public const SHIPPED = 'shipped';
}

// Uso
if ($order->status === OrderStatus::PAID) {
    // ...
}
```

## 6. Aprovecha los Array Functions

PHP tiene funciones muy útiles para arrays:

```php
$numeros = [1, 2, 3, 4, 5];

// Filtrar
$pares = array_filter($numeros, fn($n) => $n % 2 === 0);

// Mapear
$cuadrados = array_map(fn($n) => $n ** 2, $numeros);

// Reducir
$suma = array_reduce($numeros, fn($carry, $n) => $carry + $n, 0);
```

## 7. Usa Excepciones Específicas

```php
// ❌ Mal
throw new Exception('Error en el pago');

// ✅ Bien
throw new PaymentException('No se pudo procesar el pago: ' . $error);
```

## 8. Inyección de Dependencias

No uses `new` directamente en tus clases:

```php
// ❌ Mal
class UserController {
    public function index() {
        $userRepo = new UserRepository();
        // ...
    }
}

// ✅ Bien
class UserController {
    public function __construct(
        private UserRepository $userRepo
    ) {}
    
    public function index() {
        // usa $this->userRepo
    }
}
```

## 9. Usa Match Expression (PHP 8+)

Más limpio que switch:

```php
// ❌ Mal
switch ($status) {
    case 'pending':
        $message = 'Pendiente';
        break;
    case 'paid':
        $message = 'Pagado';
        break;
    default:
        $message = 'Desconocido';
}

// ✅ Bien
$message = match($status) {
    'pending' => 'Pendiente',
    'paid' => 'Pagado',
    default => 'Desconocido'
};
```

## 10. Escribe Tests

No hay excusa para no escribir tests:

```php
class UserTest extends TestCase {
    public function test_puede_crear_usuario() {
        $user = User::create([
            'name' => 'John Doe',
            'email' => 'john@example.com'
        ]);
        
        $this->assertDatabaseHas('users', [
            'email' => 'john@example.com'
        ]);
    }
}
```

## Conclusión

Estos 10 tips te ayudarán a escribir código PHP más limpio, mantenible y profesional. No necesitas aplicarlos todos de golpe, pero intenta incorporarlos gradualmente en tu día a día.

¿Qué otros tips agregarías? ¡Cuéntame en los comentarios!

---

**Tags:** #PHP #CleanCode #BestPractices #Tips
---
title: "Cómo Migrar de Base de Datos a Markdown en Laravel"
slug: "migrar-base-datos-markdown-laravel"
description: "Guía completa para convertir tu sitio Laravel de usar base de datos a archivos Markdown alojados en GitHub"
summary: "Aprende cómo puedes eliminar la dependencia de base de datos en tu portfolio y usar archivos Markdown desde GitHub como fuente de contenido."
published: true
featured: true
language: "es"
image: "https://via.placeholder.com/1200x630"
image_alt: "Laravel y Markdown"
created_at: "2024-10-10"
updated_at: "2024-10-10"
reading_time: "8 min"
tags:
  - Laravel
  - Markdown
  - JAMstack
  - Tutorial
  - PHP
category: "Backend"
author: "Tu Nombre"
---

# Cómo Migrar de Base de Datos a Markdown en Laravel

En este artículo te voy a mostrar cómo puedes transformar tu aplicación Laravel que usa base de datos a una arquitectura **JAMstack** usando archivos Markdown desde GitHub.

## ¿Por qué hacer esto?

Hay varias razones por las que podrías querer hacer esta migración:

1. **Portabilidad**: Tu contenido está versionado en Git
2. **Simplicidad**: No necesitas gestionar una base de datos
3. **Velocidad**: Con caché, es más rápido que queries
4. **Costo**: Hosting sin BD es más barato
5. **Workflow**: Editas en tu editor favorito
6. **Backup automático**: GitHub es tu backup

## Requisitos Previos

Antes de empezar, asegúrate de tener:

- Laravel 5.8 o superior
- Cuenta de GitHub
- Conocimientos básicos de Markdown
- Ganas de simplificar tu stack 😄

## Paso 1: Crear el Repositorio de Contenido

Primero, crea un repositorio público en GitHub llamado `blogcv-content`:

```bash
# En GitHub
New Repository → blogcv-content
Description: Content repository for my portfolio
Public ✓
Initialize with README ✓
```

## Paso 2: Estructura de Carpetas

Organiza tu contenido así:

```
blogcv-content/
├── profile/
│   └── info.md
├── blog/
│   └── posts/
│       └── mi-post.md
├── resume/
│   ├── education.md
│   └── experience.md
└── settings/
    └── site.md
```

## Paso 3: Crear el MarkdownService

Crea un servicio en Laravel para consumir los archivos:

```php
<?php

namespace App\Services;

use GuzzleHttp\Client;
use Parsedown;
use Symfony\Component\Yaml\Yaml;
use Illuminate\Support\Facades\Cache;

class MarkdownService
{
    protected $client;
    protected $parsedown;
    protected $repo;
    protected $branch;
    
    public function __construct()
    {
        $this->client = new Client();
        $this->parsedown = new Parsedown();
        $this->parsedown->setSafeMode(true);
        
        $this->repo = config('services.github.content_repo');
        $this->branch = config('services.github.content_branch', 'main');
    }
    
    public function getProfile()
    {
        return Cache::remember('profile_data', 3600, function() {
            return $this->getMarkdownContent('profile/info.md');
        });
    }
    
    private function getMarkdownContent($path)
    {
        $url = "https://raw.githubusercontent.com/{$this->repo}/{$this->branch}/{$path}";
        
        $response = $this->client->get($url);
        
        if ($response->getStatusCode() === 200) {
            $content = $response->getBody()->getContents();
            
            // Parsear front matter YAML
            if (preg_match('/^---\s*(.*?)\s*---(.*)/s', $content, $matches)) {
                $metadata = Yaml::parse($matches[1]);
                $markdown = $matches[2];
                
                return [
                    'metadata' => $metadata,
                    'html' => $this->parsedown->text($markdown),
                    'raw' => $markdown
                ];
            }
        }
        
        return null;
    }
}
```

## Paso 4: Actualizar el Controlador

Modifica tu controlador para usar el servicio:

```php
public function index(MarkdownService $markdown)
{
    $profile = $markdown->getProfile();
    $homeContent = $markdown->getHomeContent();
    
    return view('home', compact('profile', 'homeContent'));
}
```

## Paso 5: Configurar el .env

Agrega la configuración de tu repositorio:

```env
GITHUB_CONTENT_REPO=tu-usuario/blogcv-content
GITHUB_CONTENT_BRANCH=main
```

## Ventajas de Esta Arquitectura

✅ **Sin base de datos**: Menos complejidad en producción  
✅ **Versionado**: Todo tu contenido tiene historial  
✅ **Colaboración**: Pull requests para contribuciones  
✅ **Portabilidad**: Lleva tu contenido a donde quieras  
✅ **Económico**: Hosting más barato sin MySQL  

## Conclusión

Con esta migración, tu aplicación será más portable, más simple de mantener y más económica de hostear. El workflow de edición es más natural (editas archivos Markdown) y tienes todo el poder de Git para versionar tu contenido.

¿Tienes preguntas? ¡Déjame un comentario!

---

**Tags:** #Laravel #Markdown #JAMstack #Tutorial #PHP
# BlogCV Content Repository

Este repositorio contiene todo el contenido para mi portfolio personal en formato Markdown.

## 📁 Estructura

```
blogcv-content/
├── profile/          # Información personal
├── home/             # Contenido de la página principal
├── blog/posts/       # Posts del blog
├── resume/           # CV (educación y experiencia)
├── skills/           # Habilidades técnicas
├── about/            # Sobre mí (biografía extendida)
└── settings/         # Configuraciones del sitio
```

## ✏️ Cómo Editar

1. Edita directamente los archivos `.md` en GitHub
2. O clona el repo, edita localmente y haz push
3. Los cambios se reflejarán en el sitio (según el caché configurado)

## 📝 Formato

Todos los archivos usan:
- **Front Matter YAML** (entre `---`) para metadata
- **Markdown** para el contenido

## 🚀 Agregar un Post

1. Crea un archivo en `blog/posts/mi-nuevo-post.md`
2. Agrega el front matter con título, fecha, tags, etc.
3. Escribe el contenido en Markdown
4. Commit y push

## 📅 Última actualización

Octubre 2025

