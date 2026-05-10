![Banner](Banner_hernan_olmeda_cursor.png)

# ¡Hola a todos! 👋

Soy Hernán Olmeda, un apasionado de la tecnología 💻, la música 🎺 y la programación **</>**. Estoy estudiando 3º de la ESO y aspiro a dedicarme profesionalmente al desarrollo de software. Llevo años creando proyectos, participando en concursos de robótica y explorando diferentes áreas de la programación.

## 🛠️ Mis Habilidades Técnicas

### Lenguajes de Programación
- **Python** - Automatización, bots, IA, scripts, desarrollo de juegos
- **JavaScript / TypeScript** - Desarrollo web con React, Next.js, Node.js
- **HTML / CSS** - Diseño web responsive
- **SQL** - Bases de datos con PostgreSQL y Supabase

### Tecnologías y Herramientas
- **Frontend**: React, Next.js, Vite, Tailwind CSS, Framer Motion
- **Backend**: Node.js, FastAPI, Supabase Edge Functions, Deno
- **IA**: APIs de Groq, Cerebras, Google Gemini, OpenCV
- **Automatización**: pyautogui, PyAutoGUI, Computer Vision
- **Bases de datos**: Supabase (PostgreSQL), Backblaze B2
- **Desarrollo CLI**: Click, Rich, Textual (interfaces TUI)
- **Hardware**: Arduino, proyectos de electrónica

---

## 🚀 Proyectos Destacados

### 🌐 Desarrollo Web

#### [Locuras de Productos](https://locurasdeproductos.es)
🟢 **Estado**: Desplegado en Vercel | 🏷️ E-commerce

Página web comercial donde puedes encontrar productos únicos al mejor precio. Incluye sistema de contacto para solicitudes de productos especiales. Mi primer proyecto web publicado en producción.

#### [Tool Web](https://tool-web.vercel.app)
🟢 **Estado**: Privada (desplegada) | 🏷️ Herramientas con IA

Aplicación web full-stack con Supabase como backend (PostgreSQL + Edge Functions) e integración con Google Gemini API. Incluye herramientas varias con autenticación y base de datos.

#### [Web CNN - Private Video Viewer](https://github.com/hern-n/web_cnn)
🟡 **Estado**: Código público, despliegue privada | 🏷️ Streaming privado

Sistema de visionado de videos privado con autenticación segura:
- **Autenticación**: Contraseña con bcrypt (cost 12) y tokens JWT
- **Almacenamiento**: Backblaze B2 (compatible S3) con URLs firmadas
- **Stack**: Next.js 16 (App Router), TypeScript, Tailwind CSS
- **Protección**: Middleware con validación JWT, rutas protegidas

### 🤖 Inteligencia Artificial & Automatización

#### [BambuLab Bot](https://github.com/hern-n/bot_bambulab)
🔵 **Estado**: Activo | 🏷️ Automatización GUI

Bot de automatización de interfaces gráficas desarrollado en Python:
- **Visión por computadora**: OpenCV para template matching
- **Automatización**: pyautogui para control de mouse y teclado
- **Captura de pantalla**: Screenshot dinámico y reconocimiento de elementos
- **Configuración**: Workflows definibles via JSON
- **Email**: Integración con AgentMail API para verificación de cuentas
- **Casos de uso**: Automatización de tareas repetitivas en interfaces GUI

#### [Terminal AI Assistant](https://github.com/hern-n/terminal_ai)
🔵 **Estado**: Activo | 🏷️ Asistente CLI

Asistente de terminal que utiliza múltiples proveedores de IA gratuitos:
- **Agentes integrados**: Groq, Cerebras, Google Gemini
- **Rotación automática**: Distribuye consultas entre proveedores
- **Streaming**: Respuestas en tiempo real
- **Persistencia**: Mantiene estado del agente actual en JSON
- **Modo interactivo**: Consulta directa desde terminal

#### [English IA](https://github.com/hern-n/english_ia)
🔵 **Estado**: Activo | 🏷️ Asistente de idiomas

Asistente CLI de traducción y análisis de inglés:
- **Arquitectura de agentes**: Rotación entre Groq, Cerebras, Gemini
- **Interfaz**: CLI moderna con Rich para output visual atractivo
- **Integraciones**: Clipboard (pyperclip) para copiar resultados
- **Personalización**: Prompts del sistema configurables

#### [MultiAgent](https://github.com/hern-n/multiAgent)
🟡 **Estado**: En desarrollo | 🏷️ Sistema multi-agente

Sistema de comunicación entre agentes a través de servidor:
- **Arquitectura**: Cliente-servidor con múltiples agentes
- **Agentes disponibles**: Groq, Cerebras, Gemini
- **Comunicación**: Socket-based con sistema de mensajes

#### [Mail Dashboard - AgentMail CLI](https://github.com/hern-n/mail_dashboard)
🔵 **Estado**: Activo | 🏷️ Gestión de emails

CLI para gestionar bandejas de correo temporales:
- **Framework**: Click para CLI, Rich para output
- **TUI**: Dashboard interactivo usando Textual framework
- **API**: AgentMail SDK para crear inboxes temporales
- **Comandos**: create, list, destroy, purge, message show
- **Navegación**: Vim-like (j/k para mover, l para seleccionar)

### 🎮 Desarrollo de Juegos

#### [Frogger](https://github.com/hern-n/Frogger) - Juego de la Rana
🟢 **Estado**: Completado | 🏷️ Clásico recreado

Recreación del clásico juego arcade:
- **Objetivo**: Atrapar moscas sin ser atropellado
- **Mecánicas**: Coches desde múltiples direcciones, 9 moscas
- **Personalización**: Añadir más moscas modificando el código
- **Tecnología**: Python (pygame)

#### [Shooter Arcade](https://github.com/hern-n/Shooter-arcade) - Shooter Espacial
🟢 **Estado**: Completado | 🏷️ Clásico recreado

Recreación del juego de naves espaciales:
- **Objetivo**: Eliminar aliens y sobrevivir
- **Personalización**: Velocidad, número de aliens, tipo de balas
- **Tecnología**: Python (pygame)

#### [Rompebloques](https://github.com/hern-n/Rompebloques) - Breakout
🟢 **Estado**: Completado | 🏷️ Clásico recreado

Recreación del clásico juego de romper ladrillos:
- **Mecánicas**: Paleta controlable, bola destructora
- **Power-up**: Tecla Espacio para burst de velocidad
- **Personalización**: Velocidad de pelota, paleta y colisiones
- **Tecnología**: Python (pygame)

### 💻 Sistemas Operativos & Software

#### [NEXUS OS 2.0](https://github.com/hern-n/NEXUS_2.0)
🟡 **Estado**: En desarrollo | 🏷️ Sistema operativo web

Sistema operativo completo en el navegador:
- **Stack**: React + Vite + Tailwind CSS + Framer Motion
- **Características**:
  - Gestor de ventanas con drag y resize (mouse + touch)
  - Dock con iconos de aplicaciones
  - StatusBar con reloj y controles
  - Teclado virtual para dispositivos táctiles
  - Tema futurista con glassmorphism y efectos neon
- **Apps incluidas**: Terminal, Settings, Monitor (CPU/RAM), Files
- **Arquitectura escalable**: APP_REGISTRY para añadir apps fácilmente
- **Modo IA preparado**: Flag aiMode para integración futura

#### [Proyecto NEXUS](https://github.com/hern-n/proyecto_NEXUS)
🟡 **Estado**: En desarrollo | 🏷️ Asistente virtual

Asistente virtual con capacidades de voz:
- **Reconocimiento de voz**: speech_recognition
- **Síntesis de audio**: edge_tts (Microsoft Edge TTS)
- **Reproducción**: pygame para audio
- **Dependencias**: TogetherIA, bs4, asyncio, uuid
- **Requisito**: ffmpeg para procesamiento de audio
- **Configuración**: Instrucciones en carpeta `data/`

#### [Tasks Manager - tasks-sender](https://github.com/hern-n/tasks_manager)
🔵 **Estado**: Activo | 🏷️ CLI de notificaciones

CLI para enviar notificaciones a Telegram:
- **Concepto**: "Execute and Die" - ejecución bajo demanda
- **Integración**: Diseñado para Cron en Linux (Orange Pi, servidores)
- **Framework**: Click con python-telegram-bot (async)
- **Comandos**: send, cron, verify
- **Instalación**: pipx para instalación global

### 🔌 Plugins & Integraciones

#### [OpenClaw Plugins](https://github.com/hern-n/openclaw_plugins)
🔵 **Estado**: Activo | 🏷️ Plugin para OpenClaw

Plugin de búsqueda web para OpenClaw (gateway de IA):
- **Herramienta**: `gemini_search` para los agentes
- **Funcionalidad**: Búsqueda en Google con prefijo "gemini" para resultados de IA
- **Scraping**: Extracción de contenido de resultados
- **No requiere API keys**: Funciona fuera de la caja
- **Tecnología**: TypeScript, compatible con OpenClaw gateway

### 📱 Otros Proyectos

#### [Simple Counter](https://github.com/hern-n/simple_counter)
🟢 **Estado**: Desplegado | 🏷️ Web simple

Contador simple desplegado en Vercel.

#### [Estiramientos](https://github.com/hern-n/estiramientos)
🟢 **Estado**: Desplegado en Vercel | 🏷️ Guía fitness

Web de estiramientos y ejercicios.

#### [Recetas Virales](https://github.com/hern-n/recetasvirales)
🟢 **Estado**: Desplegado en Vercel | 🏷️ Recetas

Web de recetas de cocina.

#### [Bot BambuLab Edge](https://github.com/hern-n/bot_bambulab_edge)
🟡 **Estado**: En desarrollo | 🏷️ Automatización

Versión "edge" del bot de automatización BambuLab.

---

## 🏆 Concursos y Logros

### Robocampeones
He participado con mi equipo en el concurso de robótica **Robocampeones**. Este año planeamos construir un robot de sumo basado en Arduino. Una experiencia increíble aprendiendo sobre electrónica, programación de microcontroladores y trabajo en equipo.

---

## 📊 Stack Tecnológico Completo

| Categoría | Tecnologías |
|-----------|-------------|
| **Lenguajes** | Python, JavaScript, TypeScript, SQL |
| **Frontend** | React, Next.js, Vite, Tailwind CSS, Framer Motion |
| **Backend** | Node.js, Supabase, PostgreSQL, FastAPI |
| **IA/ML** | Groq, Cerebras, Google Gemini, OpenCV |
| **Automatización** | pyautogui, PyAutoGUI, Computer Vision |
| **CLI/TUI** | Click, Rich, Textual, Prompt Toolkit |
| **Bases de datos** | Supabase, PostgreSQL, Backblaze B2 |
| **Hardware** | Arduino, Electrónica básica |
| **DevOps** | Vercel, Git, GitHub |

---

## 📊 Estadísticas

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=hern-n&show_icons=true&theme=radical)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=hern-n&layout=compact&theme=radical)

---

## 🖥️ Mi otro perfil

Tengo otro perfil del instituto **[aquí](https://github.com/Inst-hern-n)** donde almaceno proyectos relacionados con el ámbito académico. ¡Podeis visitarlo!

---

## 📫 Contacto

- 📧 **Email**: hernan.olmeda.martin@gmail.com
- 💻 **GitHub**: https://github.com/hern-n

---

¡Gracias por visitar mi perfil! 😄

---

## Leyenda de Estados
- 🟢 **Completado/Activo**: Proyecto funcionales o publicado
- 🟡 **En desarrollo**: Proyecto en progreso
- 🔵 **Código disponible**: Repositorio público en GitHub
