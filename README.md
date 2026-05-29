<div align="center">

<!-- ═══════════════════════════════════════════════════════════ -->
<!--  ANIMATED HEADER BANNER — SVG inline (no external deps)    -->
<!-- ═══════════════════════════════════════════════════════════ -->

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 200" width="900" height="200" role="img" aria-label="Luis Antonio · ZERLB">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%"   stop-color="#04060c"/>
      <stop offset="100%" stop-color="#0d0f1e"/>
    </linearGradient>
    <linearGradient id="grad" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%"   stop-color="#6366f1"/>
      <stop offset="50%"  stop-color="#a855f7"/>
      <stop offset="100%" stop-color="#ec4899"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <!-- animated pulse circle -->
    <radialGradient id="pulse" cx="50%" cy="50%" r="50%">
      <stop offset="0%"   stop-color="#6366f1" stop-opacity="0.4"/>
      <stop offset="100%" stop-color="#6366f1" stop-opacity="0"/>
    </radialGradient>
  </defs>

  <!-- Background -->
  <rect width="900" height="200" rx="18" fill="url(#bg)"/>

  <!-- Decorative grid lines -->
  <g stroke="rgba(99,102,241,0.06)" stroke-width="1">
    <line x1="0" y1="40"  x2="900" y2="40"/>
    <line x1="0" y1="80"  x2="900" y2="80"/>
    <line x1="0" y1="120" x2="900" y2="120"/>
    <line x1="0" y1="160" x2="900" y2="160"/>
    <line x1="180" y1="0" x2="180" y2="200"/>
    <line x1="360" y1="0" x2="360" y2="200"/>
    <line x1="540" y1="0" x2="540" y2="200"/>
    <line x1="720" y1="0" x2="720" y2="200"/>
  </g>

  <!-- Ambient glow blob left -->
  <ellipse cx="60" cy="100" rx="80" ry="80" fill="url(#pulse)" opacity="0.7"/>
  <!-- Ambient glow blob right -->
  <ellipse cx="840" cy="100" rx="80" ry="80" fill="url(#pulse)" opacity="0.5"/>

  <!-- Status dot (animated pulse) -->
  <circle cx="136" cy="116" r="5" fill="#10b981" opacity="0.9">
    <animate attributeName="r" values="5;8;5" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.9;0.4;0.9" dur="2s" repeatCount="indefinite"/>
  </circle>
  <text x="148" y="120" font-family="monospace" font-size="11" fill="#9ca3af">disponible · CDMX</text>

  <!-- Main name -->
  <text x="450" y="90" text-anchor="middle" font-family="'Segoe UI',system-ui,sans-serif"
        font-size="44" font-weight="800" letter-spacing="-2" fill="url(#grad)" filter="url(#glow)">
    Luis Antonio Rosas G.
  </text>

  <!-- Handle -->
  <text x="450" y="118" text-anchor="middle" font-family="monospace" font-size="14"
        fill="rgba(255,255,255,0.35)" letter-spacing="4">
    ZERLB
  </text>

  <!-- Role line -->
  <text x="450" y="148" text-anchor="middle" font-family="'Segoe UI',system-ui,sans-serif"
        font-size="15" fill="rgba(255,255,255,0.55)" letter-spacing="0.5">
    Ing. en Sistemas · Full Stack · Redes · Virtualización XCP-ng
  </text>

  <!-- Bottom accent line -->
  <rect x="250" y="170" width="400" height="2" rx="1" fill="url(#grad)" opacity="0.6"/>
</svg>

<!-- ═══════════════════════════ TYPING SVG ═══════════════════════════ -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=3000&pause=900&color=6366F1&center=true&vCenter=true&width=700&lines=Building+systems+that+actually+matter;Full-Stack+%2B+Infrastructure+%2B+AI+Workflows;Node.js+%7C+React+%7C+PHP+%7C+Python+%7C+SQL;Cisco+CCNA+Certified+(4+modules);XCP-ng+Hypervisor+Admin+%7C+Tailscale+VPN;Mexico+City+%E2%80%94+Open+to+remote+work" alt="Typing animation"/>
</a>

<!-- ═══════════════════════════ BADGES ROW ═══════════════════════════ -->
<br/>

[![Portfolio](https://img.shields.io/badge/Portafolio-0D1117?style=for-the-badge&logo=vercel&logoColor=6366f1&label=)](https://zerlb.github.io/portafolio_luis_antonio_rosas_gomez/)&nbsp;
[![Email](https://img.shields.io/badge/luisrosasgom%40gmail.com-0D1117?style=for-the-badge&logo=gmail&logoColor=ea4335)](mailto:luisrosasgom@gmail.com)&nbsp;
[![GitHub](https://img.shields.io/badge/ZERLB-0D1117?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ZERLB)&nbsp;
<img src="https://komarev.com/ghpvc/?username=ZERLB&style=for-the-badge&color=0D1117&label=VIEWS" alt="Profile views"/>

</div>

---

## 👨🏻‍💻 Sobre mí · About Me

Soy **Ingeniero en Sistemas Computacionales** y **Full Stack Developer** en la Ciudad de México.  
Diseño e implemento sistemas modulares de alto rendimiento: APIs RESTful robustas, infraestructura virtualizada, redes empresariales seguras y automatizaciones avanzadas.

| | |
|---|---|
| **Institución actual** | T.O.C. en Dirección de Tecnologías · [UNISA](https://www.unisa.cdmx.gob.mx/) |
| **Impacto** | Sistemas con **+2,000 usuarios activos diarios** en producción |
| **Infraestructura** | Pool de hipervisores **XCP-ng 8.2** · 24 VMs · 72 vCPUs · 256 GB RAM |
| **Redes** | Core Switches · VLANs · Firewall Hillstone · **Tailscale VPN** |
| **Certificaciones** | **Cisco CCNA** R&S — 4 módulos aprobados |
| **Disponibilidad** | Proyectos remotos / freelance — [luisrosasgom@gmail.com](mailto:luisrosasgom@gmail.com) |

---

## 🛠️ Stack Tecnológico

<div align="center">

**Backend & Languages**

<img src="https://skillicons.dev/icons?i=ts,js,nodejs,express,py,php,bash&perline=8"/>

**Frontend**

<img src="https://skillicons.dev/icons?i=react,vite,tailwind,html,css,materialui&perline=8"/>

**Databases & DevOps**

<img src="https://skillicons.dev/icons?i=postgres,mysql,docker,ubuntu,linux,git,github&perline=8"/>

**Infraestructura & Herramientas**

<img src="https://cdn.simpleicons.org/citrix/005571" width="34" title="XCP-ng / XenServer"/>&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/prisma/2D3748" width="34" title="Prisma ORM"/>&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/notion/ffffff" width="34" title="Notion API"/>&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/nginx/009639" width="34" title="Nginx"/>&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/pm2/2B037A" width="34" title="PM2"/>&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/tailscale/242424" width="34" title="Tailscale VPN"/>&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/warp/01A4FF" width="34" title="Warp Terminal"/>

</div>

---

## 📊 Estadísticas de Desarrollo

<div align="center">
  <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=ZERLB&show_icons=true&theme=tokyonight&hide_border=true&bg_color=04060c&icon_color=6366f1&title_color=a855f7&text_color=9ca3af&include_all_commits=true&count_private=true" width="49%"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ZERLB&theme=tokyonight&hide_border=true&background=04060c&ring=6366f1&fire=ec4899&currStreakLabel=a855f7" width="49%"/>
</div>
<div align="center">
  <img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=ZERLB&layout=compact&theme=tokyonight&hide_border=true&bg_color=04060c&title_color=a855f7&text_color=9ca3af&langs_count=8" width="49%"/>
</div>

---

## 🔥 Proyectos Destacados

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">
        <a href="https://github.com/ZERLB/app_Savitar">⚡ Savitar — Server Monitor</a>
      </h3>
      <p align="center">
        Dashboard personal de monitoreo de infraestructura con terminales SSH en tiempo real, sincronización bidireccional con Notion, panel de control de VMs XCP-ng estilo XenCenter, rastreador de hábitos y asistente AI integrado.
      </p>
      <div align="center">
        <img src="https://skillicons.dev/icons?i=ts,react,nodejs,postgres"/>
      </div>
      <p align="center">
        <img src="https://img.shields.io/badge/TypeScript-007acc?style=flat-square&logo=typescript&logoColor=white"/>
        <img src="https://img.shields.io/badge/React-61dafb?style=flat-square&logo=react&logoColor=black"/>
        <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">
        <a href="https://github.com/ZERLB">🏢 NEXUS / SIGU — Sistema Universitario</a>
      </h3>
      <p align="center">
        Sistema modular universitario para calificaciones, servicios escolares, registros académicos y Títulos Electrónicos SEP (SOAP/XML). Soporta <strong>+2,000 usuarios diarios</strong> sobre infraestructura local segura.
      </p>
      <div align="center">
        <img src="https://skillicons.dev/icons?i=nodejs,react,mysql,ubuntu"/>
      </div>
      <p align="center">
        <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white"/>
        <img src="https://img.shields.io/badge/MySQL-4479a1?style=flat-square&logo=mysql&logoColor=white"/>
        <img src="https://img.shields.io/badge/React-61dafb?style=flat-square&logo=react&logoColor=black"/>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">
        <a href="https://github.com/ZERLB/correos_masivos">📧 Bulk Mailer Campaign Engine</a>
      </h3>
      <p align="center">
        Motor de envío masivo de correos basado en hojas de cálculo. Incluye throttling automático, validación anti-rebote, plantillas HTML avanzadas y tasas de entrega optimizadas.
      </p>
      <div align="center">
        <img src="https://skillicons.dev/icons?i=react,nodejs,express,tailwind"/>
      </div>
      <p align="center">
        <img src="https://img.shields.io/badge/React-61dafb?style=flat-square&logo=react&logoColor=black"/>
        <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">
        <a href="https://github.com/ZERLB/consultorio_unisa">🩺 Clinical Consults v2</a>
      </h3>
      <p align="center">
        Sistema Full Stack de expedientes médicos: historial de pacientes, registros de consultas, agenda activa y flujos de trabajo clínico para el consultorio universitario de la UNISA.
      </p>
      <div align="center">
        <img src="https://skillicons.dev/icons?i=react,express,mysql,css"/>
      </div>
      <p align="center">
        <img src="https://img.shields.io/badge/React-61dafb?style=flat-square&logo=react&logoColor=black"/>
        <img src="https://img.shields.io/badge/MySQL-4479a1?style=flat-square&logo=mysql&logoColor=white"/>
      </p>
    </td>
  </tr>
</table>

---

<details>
<summary><b>🇲🇽 Ver versión en español completa</b></summary>

<br/>

Soy **Ingeniero en Sistemas Computacionales** y **Desarrollador Full Stack** en la Ciudad de México. Me especializo en el diseño e implementación de sistemas modulares, bases de datos relacionales y despliegues estables en infraestructuras de red seguras.

- **Desarrollo Institucional:** Desarrollador principal de **NEXUS** y **SIGU** en [UNISA](https://www.unisa.cdmx.gob.mx/), soportando **+2,000 usuarios activos diarios**.
- **Virtualización e Infraestructura:** Administración de pools de hipervisores **XCP-ng (XenServer)**, almacenamiento NAS unificado y redes con Tailscale VPN.
- **Seguridad de Redes:** 4 módulos aprobados de **Cisco CCNA R&S** — switches Core, firewalls Hillstone y VLANs corporativas.
- **Integración Gubernamental:** Títulos Electrónicos oficiales firmados digitalmente para la **SEP** via SOAP/XML.

> 💼 **Disponible para proyectos remotos y freelance.** Diseño backend, APIs personalizadas, automatización de scripts, dashboards avanzados y despliegue de sistemas. → [luisrosasgom@gmail.com](mailto:luisrosasgom@gmail.com)

</details>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=100&section=footer" alt="Footer wave"/>
  <p><strong>¿Tienes un proyecto interesante? <a href="mailto:luisrosasgom@gmail.com">Hablemos →</a></strong></p>
</div>
