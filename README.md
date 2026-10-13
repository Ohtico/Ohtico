<div align="center">

# 👋 Víctor Gelvis
### Senior Full-stack & AI Solutions Developer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ohtico)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vgelvisoviedo@gmail.com)
[![Location](https://img.shields.io/badge/Bogotá,_Colombia-🇨🇴-green?style=for-the-badge)](https://maps.google.com/?q=Bogotá,Colombia)

</div>

---

## 👨‍💻 Sobre mí

Desarrollador **Full-stack Senior** que empezó en el front-end (**React**, **React Native**, **TypeScript**) y hoy construye de punta a punta sobre **Python** y **AWS**: desde la UI hasta los backends, las Lambdas y la infraestructura. Me especializo en productos que combinan **IA generativa** (LLMs, extracción de documentos, speech-to-text) con plataformas SaaS **multi-tenant**.

Mi forma de trabajar: **medir antes de decidir**. Varias de mis mejores decisiones técnicas salieron de un número medido que cambió el diseño, recortó el alcance o bajó el costo en órdenes de magnitud.

---

## 🛠️ Stack Tecnológico

### Front-end
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Back-end & Datos
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white)
![Meilisearch](https://img.shields.io/badge/Meilisearch-FF5CAA?style=for-the-badge&logo=meilisearch&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

### AI & Cloud
![AWS](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![Amazon Bedrock](https://img.shields.io/badge/Amazon_Bedrock-01A88D?style=for-the-badge&logo=amazonaws&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-CC785C?style=for-the-badge&logo=anthropic&logoColor=white)
![Amazon Connect](https://img.shields.io/badge/Amazon_Connect-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Textract](https://img.shields.io/badge/Textract-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)

### Testing & Herramientas
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Cypress](https://img.shields.io/badge/Cypress-17202C?style=for-the-badge&logo=cypress&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-323330?style=for-the-badge&logo=jest&logoColor=C21325)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-CC785C?style=for-the-badge&logo=anthropic&logoColor=white)

---

## 🏆 Logros destacados

| Logro | Resultado |
|---|---|
| 📐 Corrección de la ubicación de datos extraídos por IA en documentos | **85% → 0%** de resaltados mal ubicados |
| 🎙️ Transcripción de notas de voz con Bedrock en vez de Amazon Transcribe | **~660× más barato**, sin cambiar la infraestructura de ningún cliente |
| 🧭 Clasificación de documentos en cascada (proveedor → tipo) | Las tipologías **se suman en vez de multiplicarse**; un proveedor nuevo es una rama nueva, no un rediseño |
| 🔒 Segmentación de agentes por caso de uso en REST **y** WebSocket | Aislamiento real de datos, transferencias y derivación automática del bot |
| 📝 Features especificadas de punta a punta | **+15** HUs con criterios EARS/INVEST, diseño técnico y ADRs |

---

## 💼 Experiencia Profesional

### 🚀 Senior Full-stack & AI Solutions Developer
**Independent Contractor** · Remoto, Bogotá · *Jul 2025 – Presente*

Trabajo en una **plataforma BPO SaaS multi-tenant** sobre AWS: un **Centro de Atención (call center omnicanal con WhatsApp y Amazon Connect)** y un motor de **procesamiento inteligente de documentos** (IPA). Implemento en simultáneo el front-end y tres backends en Python; la mayoría de mis entregas cruzan las cuatro capas.

**🤖 IA y procesamiento de documentos**
- 📐 Diagnostiqué que **Bedrock Data Automation** ubica mal los valores repetidos en tablas y diseñé un **re-anclaje de geometría** (grilla del documento + consenso por fila) que llevó el error de **85% a 0%**. Hoy corre en producción
- 🧭 **Clasificadores encadenados** (1 → N): un primer nivel identifica el proveedor y enruta a un clasificador por proveedor, con caché de documento entre eslabones y registro de consumo de tokens por invocación
- 📄 **Reconstrucción de tablas multipágina** con **Amazon Textract** (OCR asíncrono) y procesamiento de lotes tolerante a errores parciales
- 🧮 Especificación de un **motor de tablas** con fórmulas, series y referencias cruzadas dinámicas
- 📊 Reportes **CSV consolidados por lote** con plantillas y export plano a demanda sobre cualquier selección de resultados
- 🛠️ Creé un **subagente de IA reutilizable** que arma componentes de extracción a partir de documentos de referencia y verifica el resultado contra los archivos fuente

**💬 Centro de Atención omnicanal**
- 🎙️ **Audio entrante por WhatsApp**: antes de escribir código comparé **7 motores de speech-to-text** con tráfico real. Elegí Voxtral vía Bedrock y transcodifiqué con PyAV en 4–34 ms. Ahora el bot entiende notas de voz y llena los campos del caso de uso
- 🖼️ **Multimedia entrante y saliente**: el bot, las campañas y los agentes envían imágenes, y todos los archivos recibidos pasan por **escaneo antimalware (GuardDuty)**, validación de contenido y límites de tamaño
- 🔀 **Segmentación por casos de uso**: roster agente↔caso de uso, aislamiento en REST/Meilisearch **y** WebSocket, transferencia de chats con trazabilidad y **derivación automática del bot** con límites configurables
- 📈 **Eventos de negocio** (`business_events`): webhook con dual-write para migrar sin cortes, catálogo de atributos, evento de conversión, **tarjetas de KPI configurables** con sparklines y búsqueda de eventos para **armar audiencias de campaña**
- ⏰ **Recordatorios configurables**: reglas por caso de uso con plantillas de WhatsApp, una Lambda despachadora, reconciliación de schedules y estadísticas diarias
- 🔌 Integraciones vía **MCP** con firma de remitente, documentación de APIs públicas (ReDoc) y gestión de API keys

**🧠 Ingeniería asistida por IA**
- Escribo y mantengo **especificaciones** (requirements + design + worklog) validadas contra **INVEST/EARS**, y registro las decisiones de arquitectura en **ADRs**
- Trabajo con **Claude Code**, workflows y subagentes especializados para especificar, implementar, revisar y hacer QA de las entregas
- 🔒 Detecté y ayudé a cerrar riesgos de **privacidad de datos**, como fugas entre casos de uso o acceso indebido a archivos de contactos

---

### 💼 Front-end Developer MID
**Rebus Technology** · Remoto, Bogotá · *Abr 2023 – Jul 2025*

- 📱 Lideré el desarrollo de **aplicaciones móviles en React Native** para iOS y Android
- ⚡ Construí componentes reutilizables de alto rendimiento que mejoraron la UX
- 🚀 Gestioné los lanzamientos en **App Store Connect** y **Google Play Console**
- 🔗 Configuré **deep linking**, atribución con Branch.io y notificaciones push segmentadas
- ✅ Aseguré la calidad con pruebas unitarias (**Jest**) y E2E (**Cypress**)

---

### 💼 Front-end Developer
**Technisupport S.A.S** · Bogotá · *Dic 2021 – Abr 2023*

- 🧩 Desarrollé interfaces modulares en **React.js** con manejo de estado complejo en Redux
- 🎨 Trabajé con equipos de UI/UX para convertir prototipos en productos funcionales y escalables

---

## 🧪 Proyectos personales

| Proyecto | Descripción | Stack |
|---|---|---|
| 💰 **Flowi** | Finanzas personales y familiares: ingresos y gastos por categoría, tarjeta de crédito con cobro diferido, modo familia y gráficos de tendencia en tiempo real | React 19 · Vite · Tailwind 4 · Firebase · Playwright |
| 🏢 **Brixel** | Prototipo de SaaS de gestión empresarial con IA generativa, CI y git hooks | React 19 · TypeScript · Vite · Gemini API |

---

## 🌐 Idiomas

| Idioma | Nivel |
|--------|-------|
| 🇪🇸 Español | Nativo |
| 🇺🇸 Inglés | Básico |

---

## 📈 GitHub Stats

> Casi todo mi trabajo vive en repositorios privados de la organización, así que estas métricas salen de mi historial de git real y no de mis repos públicos.

<div align="center">

![Pull Requests](https://img.shields.io/badge/Pull_Requests-353-8B5CF6?style=for-the-badge&logo=githubactions&logoColor=white)
![Merged](https://img.shields.io/badge/Mergeados-323_(91%25)-22C55E?style=for-the-badge&logo=git&logoColor=white)
![Commits](https://img.shields.io/badge/Commits-739-F97316?style=for-the-badge&logo=git&logoColor=white)
![Repos](https://img.shields.io/badge/Repositorios-7-0EA5E9?style=for-the-badge&logo=github&logoColor=white)
![Week streak](https://img.shields.io/badge/Racha-37_semanas-EF4444?style=for-the-badge&logo=github&logoColor=white)

<sub>Jul 2025 – Oct 2026 · sin contar commits automáticos de deploy</sub>

</div>

### 🧬 En qué escribo hoy

| Lenguaje | Proporción | |
|---|---|---|
| ![TypeScript](https://img.shields.io/badge/-TypeScript-007ACC?logo=typescript&logoColor=white) | `█████████████░░░░░░░` | **62%** |
| ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) | `████░░░░░░░░░░░░░░░░` | **21%** |
| ![Markdown](https://img.shields.io/badge/-Specs_&_ADRs-000000?logo=markdown&logoColor=white) | `███░░░░░░░░░░░░░░░░░` | **17%** |

<sub>Líneas añadidas por mí en los repos de la plataforma, sin contar JSON/YAML, lockfiles ni archivos generados.</sub>

<div align="center">
  <img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Ohtico&theme=tokyonight" alt="Contribuciones de Víctor" />
  <br/>
  <img height="165" src="https://streak-stats.demolab.com?user=Ohtico&theme=tokyonight&hide_border=true&mode=weekly" alt="Racha semanal" />
</div>

---

<div align="center">

*"La mejor arquitectura es la que el usuario nunca nota — solo siente."*

⭐ Si alguno de mis proyectos te fue útil, considera dejar una estrella!

</div>
