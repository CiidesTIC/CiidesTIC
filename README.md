<p align="center">
  <img src="https://ciidesbic.org/Logo_CiidesBIC.jfif" alt="CIIDES S.A.S. BIC" height="96" />
</p>

<p align="center">
  <strong>CiidesTIC · División de Tecnologías de la Información y las Comunicaciones</strong><br />
  Centro de Investigación, Innovación y Desarrollo para la Sustentabilidad (CIIDES S.A.S. BIC)<br />
  Florencia, Caquetá, Colombia
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Astro-BC52EE?logo=astro&logoColor=white" alt="Astro">
  <img src="https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Directus-64f?logo=directus&logoColor=white" alt="Directus">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black" alt="Linux">
</p>

<p align="center">
  <a href="#sobre-ciidestic">Sobre CiidesTIC</a> ·
  <a href="#líneas-de-acción">Líneas de acción</a> ·
  <a href="#ecosistema-de-servicios">Ecosistema</a> ·
  <a href="#stack-tecnológico">Stack tecnológico</a> ·
  <a href="#estándares-de-desarrollo">Estándares</a> ·
  <a href="#contacto-institucional">Contacto</a>
</p>

---

## Sobre CiidesTIC

**CiidesTIC** es la división de desarrollo tecnológico e innovación de **CIIDES S.A.S. BIC** (Centro de Investigación, Innovación y Desarrollo para la Sustentabilidad). Este espacio centraliza los proyectos de software, plataformas de divulgación científica, soluciones digitales y flujos de automatización que respaldan la labor investigativa, editorial y de desarrollo regional en la Amazonía colombiana.

> Impulsando el desarrollo regional mediante Ciencia, Tecnología e Innovación (CTeI), automatización de procesos y rigor científico.

### Objetivo y alcance institucional

| Dimensión | Definición |
|---|---|
| **Propósito** | Diseñar, desarrollar y operar soluciones tecnológicas robustas que optimicen la investigación científica, la publicación académica y la gestión de proyectos de sustentabilidad. |
| **Comunidad y usuarios** | Investigadores, comités editoriales, pares evaluadores, desarrolladores de software y entidades públicas y privadas aliadas. |
| **Alcance técnico** | APIs REST, aplicaciones web SPA/SSR, infraestructura cloud y on-premise, automatización de procesos mediante n8n, y plataformas editoriales académicas. |

---

## Líneas de acción

<details open>
<summary><strong>Plataformas y aplicaciones CTeI</strong></summary>

- Construcción de aplicaciones web orientadas a la captura, procesamiento y visualización de datos de investigación.
- Implementación de arquitecturas modernas y modulares basadas en interfaces desacopladas (Headless CMS y APIs REST).
- Interfaces de usuario optimizadas para accesibilidad, rendimiento y compatibilidad multiplataforma.

</details>

<details>
<summary><strong>Sistemas de publicación y gestión editorial</strong></summary>

- Despliegue y administración de plataformas Open Journal Systems (OJS) y Open Monograph Press (OMP) para el Sello Editorial CIIDES.
- Configuración de protocolos de interoperabilidad científica (OAI-PMH, asignación y validación de metadatos DOI y ORCID).
- Preservación digital y flujos de trabajo editoriales con revisión por pares.

</details>

<details>
<summary><strong>Automatización de flujos y orquestación de datos</strong></summary>

- Integración continua entre sistemas dispares a través de webhooks y servicios de orquestación (n8n).
- Automatización de notificaciones, sincronización de bases de datos y procesamiento en segundo plano.
- Reducción de fricción operativa en procesos de evaluación, registro y reporte.

</details>

<details>
<summary><strong>Infraestructura, servidores y operaciones</strong></summary>

- Administración de infraestructura de servidores y clústeres de contenedores Docker.
- Implementación de entornos de integración y entrega continua (CI/CD) para despliegues trazables y seguros.
- Políticas de respaldo automatizado, monitoreo de servicios y hardening de seguridad en servidores.

</details>

---

## Ecosistema de servicios

| Componente | Rol en la infraestructura | Tecnologías principales | Descripción |
|---|---|---|---|
| **Sistemas Editoriales** | Publicación académica | OJS · OMP · PHP · MySQL | Gestión del ciclo editorial de revistas científicas y libros académicos con revisión por pares. |
| **Capa de Contenido (Headless BaaS)** | Gestión central de datos | Directus · PostgreSQL | Backend centralizado, modelado dinámico de esquemas y provisión de APIs REST/GraphQL. |
| **Plataformas Web CTeI** | Presentación y divulgación | React · Vite · Astro · Tailwind CSS | Portales institucionales de alto rendimiento y herramientas web de análisis y seguimiento. |
| **Motor de Automatización** | Orquestación de procesos | n8n · Node.js · Webhooks | Flujos automáticos de ingestión, validación de datos y comunicación entre plataformas. |
| **Capa de Despliegue e Infraestructura** | Infraestructura y hosting | Docker · Dokploy · Linux | Contenedorización, gestión de servicios y despliegues productivos. |

---

## Stack tecnológico

| Capa | Tecnologías | Rol en el ecosistema |
|---|---|---|
| **Frontend** | Astro · React · Vite · Tailwind CSS | Interfaces web estáticas optimizadas, portales de divulgación y SPAs interactivas. |
| **Backend & Microservicios** | Node.js (Express) · Python | Desarrollo de endpoints REST, procesamiento analítico de datos y microservicios. |
| **Gestión de Contenido & BaaS** | Directus | Panel administrativo desacoplado, control de acceso basado en roles (RBAC) y APIs dinámicas. |
| **Sistemas Académicos** | Open Journal Systems (OJS) · Open Monograph Press (OMP) | Ecosistema de publicación científica, indización y difusión de literatura académica. |
| **Bases de Datos** | PostgreSQL · MongoDB · SQLite | Persistencia relacional, documental y embebida con esquemas normalizados y auditoría. |
| **Automatización** | n8n · Webhooks | Integraciones asíncronas entre plataformas, alertas y canalización de eventos. |
| **Infraestructura & DevOps** | Docker · Dokploy · Linux · Nginx | Aislamiento en contenedores, gestión de servidores, proxies inversos y pipelines de despliegue. |

---

## Estándares de desarrollo

- **Arquitectura desacoplada:** Separación clara entre capas de presentación, lógica de negocio y persistencia.
- **Seguridad y trazabilidad:** Manejo estricto de variables de entorno, control de acceso por roles (RBAC) y registros de auditoría.
- **Ciencia Abierta:** Adopción de estándares internacionales de metadatos abiertos, protocolos OAI-PMH e identificación persistente.
- **Documentación continua:** Especificaciones técnicas estandarizadas mediante OpenAPI / Scalar para todas las APIs institucionales.

---

## Contacto institucional

| Canal | Detalle |
|---|---|
| **Entidad** | CIIDES S.A.S. BIC · Centro de Investigación, Innovación y Desarrollo para la Sustentabilidad |
| **División** | CiidesTIC (Tecnologías de la Información y las Comunicaciones) |
| **Sede** | Florencia, Caquetá, Colombia |
| **Portal institucional** | [Site Ciides S.A.S. BIC](https://ciidesbic.org/) |
| **Sello Editorial** | [Publicaciones y Fondo Editorial CIIDES](https://ciidesbic.org/editorial) |
| **Repositorio central** | [GitHub CiidesTIC](https://github.com/CiidesTIC) |

---

<p align="center">
  <small>© Centro de Investigación, Innovación y Desarrollo para la Sustentabilidad (CIIDES S.A.S. BIC). Todos los derechos reservados.</small>
</p>
