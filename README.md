<div align="center">

<h1>Jesús Cueto | Software Engineer & Arquitectura Web</h1>

<p>
  Ingeniero de software enfocado en productos de alto impacto: arquitecturas limpias, backend transaccional de alta concurrencia, interfaces web reactivas, algoritmos de optimización logística e integración de LLMs con bases de datos mediante Model Context Protocol (MCP) y RAG.
</p>

<p>
  <img alt="Engineering" src="https://img.shields.io/badge/Engineering-Architecture%20%26%20Clean%20Code-111827?style=for-the-badge">
  <img alt="AI Applied" src="https://img.shields.io/badge/IA%20Aplicada-LLMs%20%2B%20MCP%20%2B%20RAG-6d28d9?style=for-the-badge">
  <img alt="Backend" src="https://img.shields.io/badge/Backend-NestJS%20%2B%20Node.js%20%2B%20Python-0f766e?style=for-the-badge">
  <img alt="Frontend" src="https://img.shields.io/badge/Frontend-Vue%203%20%2B%20Flutter%20Web%20%2B%20TypeScript-2563eb?style=for-the-badge">
  <img alt="Data Systems" src="https://img.shields.io/badge/Data%20Systems-PostgreSQL%20%2B%20CockroachDB%20%2B%20Redis-b45309?style=for-the-badge">
</p>

<table>
  <tr>
    <td align="center"><strong>Arquitectura</strong><br>Monorepos, modularidad, bajo acoplamiento, DTOs y contratos tipados</td>
    <td align="center"><strong>Sistemas Transaccionales</strong><br>Concurrencia con bloqueo pesimista, ventanas de idempotencia y resiliencia offline</td>
    <td align="center"><strong>IA & Agentes</strong><br>Servidores MCP, asistentes con contexto RAG y flujos Human-in-the-Loop</td>
    <td align="center"><strong>Cloud & DevOps</strong><br>Contenedores Docker, CI/CD con GitHub Actions, Cloudflare Workers y Railway</td>
  </tr>
</table>

</div>

## GitHub Stats

<div align="center">
  <table>
    <tr>
      <td>
        <a
          href="https://github.com/JesusC1755?tab=overview"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="Ver estadísticas de GitHub de Jesús Cueto"
        >
          <img
            src="https://github-readme-stats.vercel.app/api?username=JesusC1755&show_icons=true&count_private=true&include_all_commits=true&theme=tokyonight&hide_border=false"
            alt="GitHub Stats de Jesús Cueto"
          >
        </a>
      </td>
    </tr>
    <tr>
      <td>
        <a
          href="https://github.com/JesusC1755"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="Ver racha de contribuciones de Jesús Cueto"
        >
          <img
            src="https://streak-stats.demolab.com?user=JesusC1755&hide_border=false&border=e4e2f4&background=141321&stroke=e4e2f4&ring=ff2e93&fire=ff2e93&currStreakNum=f8d847&sideNums=ff2e93&currStreakLabel=f8d847&sideLabels=ff2e93&dates=9dfcff&locale=es"
            alt="Racha de contribuciones de GitHub"
          >
        </a>
      </td>
    </tr>
    <tr>
      <td>
        <a
          href="https://github.com/JesusC1755?tab=repositories"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="Ver lenguajes más usados de Jesús Cueto"
        >
          <img
            src="https://github-readme-stats.vercel.app/api/top-langs?username=JesusC1755&layout=compact&langs_count=8&theme=tokyonight&hide_border=false"
            alt="Lenguajes más usados en GitHub"
          >
        </a>
      </td>
    </tr>
  </table>
</div>

## Perfil técnico

Egresado de Ingeniería de Sistemas en proceso de grado en la **Universidad de La Guajira**, con trayectoria en diseño y desarrollo de software full stack. Mi experiencia abarca desde el modelado relacional estricto y la orquestación de sistemas transaccionales hasta la construcción de herramientas asistidas por inteligencia artificial (RAG, Model Context Protocol) para resolver casos de negocio reales.

El enfoque técnico de mis desarrollos prioriza:
* **Integridad transaccional y concurrencia**: Protección de estados críticos de datos mediante bloqueos pesimistas, claves de idempotencia y trazabilidad de eventos.
* **Separación de responsabilidades**: Arquitecturas modulares basadas en contratos formales (DTOs, esquemas tipados) que aíslan la lógica de dominio de los proveedores de infraestructura.
* **Resiliencia en cliente**: Implementación de arquitecturas reactivas con tolerancia a desconexión mediante colas de mutaciones offline y sincronización en segundo plano.

---

## Proyectos destacados (Colaboraciones)

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>01. CourseV</h3>
      <p><strong>Plataforma educativa full stack con IA generativa, RAG, Model Context Protocol (MCP) y asistencia docente interactiva.</strong></p>
      <p>
        Solución integral para diseñar, estructurar y gestionar cursos, tareas y contenidos académicos. Conecta modelos de lenguaje con la base de conocimiento y el dominio de la plataforma para automatizar la labor pedagógica sin perder el control humano.
      </p>
      <p>
        <strong>Especialidad:</strong> Model Context Protocol (MCP), RAG, LLMs, Vue 3, TypeScript, PWA, Node.js, Express, Socket.io, Supabase, PostgreSQL (pgvector) y Cloudflare R2.
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>02. Cobro</h3>
      <p><strong>Monorepo fintech para gestión de créditos, tesorería de caja menor y optimización logística de cobranza en campo.</strong></p>
      <p>
        Sistema empresarial distribuido que orquesta desembolsos, pagos transaccionales con bloqueo pesimista, ruteo georreferenciado con Dijkstra, pasarela de mensajería WhatsApp y cliente web con soporte offline.
      </p>
      <p>
        <strong>Especialidad:</strong> NestJS, TypeScript, Prisma ORM, CockroachDB Cloud, PostgreSQL 15, Flutter Web, Dart, Next.js 19, OSRM, Evolution API y Docker Compose.
      </p>
    </td>
  </tr>
</table>

---

## Proyecto 01: CourseV

CourseV es una plataforma educativa creada para modernizar el aprendizaje digital y reducir la carga operativa docente mediante agentes inteligentes. Integra una Progressive Web App (PWA) reactiva en Vue 3 con un backend modular en Node.js/Express y servicios estandarizados de IA.

El valor central del sistema reside en conectar agentes LLM con herramientas de dominio autorizadas mediante el estándar **Model Context Protocol (MCP)**, garantizando que el asistente opere sobre el contexto curricular real y genere planes de estudio editables bajo un flujo *Human-in-the-loop*.

<div align="center">
  <a href="https://github.com/Jesuh02/MCP-backendDeploy" target="_blank" rel="noopener noreferrer">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Jesuh02&repo=MCP-backendDeploy&theme=tokyonight&hide_border=false" alt="CourseV Backend MCP" width="48%" />
  </a>
  <a href="https://github.com/Jesuh02/coursev_web_frontend" target="_blank" rel="noopener noreferrer">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Jesuh02&repo=coursev_web_frontend&theme=tokyonight&hide_border=false" alt="CourseV Frontend" width="48%" />
  </a>
</div>

### Arquitectura y decisiones técnicas

| Decisión técnica | Justificación e impacto |
| :--- | :--- |
| **Model Context Protocol (MCP)** | Desacoplamiento de herramientas de IA: permite al agente interactuar con el modelo de datos de cursos y tareas sin enlazar la lógica al proveedor del LLM. |
| **RAG sobre base vectorial** | Consultas contextualizadas sobre material de estudio y rúbricas almacenadas en **PostgreSQL con pgvector**, reduciendo alucinaciones en respuestas a estudiantes. |
| **Arquitectura de frontend modular** | Organización *feature-driven* en Vue 3 con Pinia para un flujo de estado reactivo y rutas protegidas con validación de roles y permisos. |
| **Generación asíncrona de recursos** | Despacho fuera del hilo principal para la creación de guías en Word/PDF, miniaturas y materiales multimedia almacenados en Cloudflare R2. |
| **Validación de contratos en API** | Esquemas Joi en los bordes de entrada para sanitizar payloads antes de invocar casos de uso o herramientas MCP. |

### Flujo de creación curricular con IA

```mermaid
sequenceDiagram
  participant Docente
  participant PWA as Vue 3 PWA
  participant IA as LLM Agent
  participant MCP as MCP Tools
  participant API as Backend (Node.js)
  participant DB as Supabase / pgvector
  participant R2 as Cloudflare R2

  Docente->>PWA: Define objetivo y alcance del curso
  PWA->>IA: Envía prompt con contexto pedagógico
  IA->>MCP: Invoca herramientas de dominio del curso
  MCP->>API: Ejecuta reglas de negocio y formula estructura
  API->>PWA: Retorna propuesta curricular editable
  Docente->>PWA: Revisa, ajusta parámetros y confirma
  PWA->>API: Persiste curso y módulos
  API->>DB: Almacena materias, tareas y embeddings
  API->>R2: Publica recursos complementarios en background
