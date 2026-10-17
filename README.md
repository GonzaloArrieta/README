# Hola, soy Gonzalo Arrieta 👋

### AI Automation Engineer · Buenos Aires, Argentina

Construyo agentes de IA y automatizaciones para problemas reales de negocio. Antes de la tecnología trabajé 4 años en operaciones: logística, coordinación de equipos, e-commerce y atención al cliente. Sé cómo funciona una operación por dentro antes de proponer qué automatizar.

---

## 🔧 En qué estoy trabajando

### [velia-core](https://github.com/GonzaloArrieta/velia-core)

Núcleo en Python de Velia, un agente de IA para WhatsApp pensado para inmobiliarias.

- Webhook en **FastAPI** que valida cada mensaje y descarta duplicados con una restricción única en **PostgreSQL**.
- **Clasificador de consultas** (interesado, cliente o spam) con un **set de evaluación** de 20 casos reales del rubro: acierta 20 de 20.
- **Tests con pytest**, imagen de **Docker** y **CI en GitHub Actions** que corre todo contra una base temporal en cada push.

### [Velia](https://veliapp.com.ar)

Empezó como emprendimiento y hoy es mi laboratorio. La primera versión funciona en n8n:

- Responde texto, audio (transcripción con Whisper) e imágenes por WhatsApp, con memoria de conversación por contacto.
- Arquitectura multi-tenant con aislamiento por organización (**Row-Level Security** en Supabase).
- Dashboard por organización en Next.js sobre Vercel.
- Resolví problemas reales de confiabilidad: mensajes duplicados, cambios de formato de la API de WhatsApp y el retiro de un modelo por parte del proveedor.
- Revisión de seguridad con corrección de los hallazgos: límites a la entrada del usuario, delimitación de prompts y errores que no exponen información interna.
- Llevé también la parte comercial: más de 160 inmobiliarias relevadas, 90 contactadas y demos.

---

## 🧪 Cómo trabajo

Vengo de QA. Pienso en casos borde, manejo de errores y en que las cosas funcionen fuera de la demo. Y mido antes de cambiar: si toco un prompt, vuelvo a correr el set de evaluación.

---

## 🛠 Stack

**IA:** APIs de Anthropic, OpenAI y Groq · Whisper · prompt engineering · guardrails
**Backend y datos:** Python · FastAPI · PostgreSQL · Supabase · APIs REST · webhooks · Evolution API
**Testing:** pytest · Postman · Selenium · Cucumber
**Infraestructura:** Docker · GitHub Actions · n8n self-hosted · Easypanel · Vercel · Git
**Frontend:** Next.js

---

## 📫 Contacto

- 💼 [LinkedIn](https://linkedin.com/in/pablo-gonzalo-arrieta)
- 📧 pablogonzaloarrieta7@gmail.com
- 📍 Caseros, Buenos Aires (UTC-3)

Busco roles de **AI Automation, Implementation o Solutions Engineer**, híbridos o presenciales en Buenos Aires.
