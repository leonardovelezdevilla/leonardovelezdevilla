# Hola, soy Leonardo Vélez De Villa 👋

Estudiante de último ciclo de Ingeniería Industrial (UNFV, décimo superior; egreso dic. 2026) que convierte necesidades de usuarios en productos digitales usando IA. Levanto requerimientos, prototipo, pruebo antes de desplegar y documento.

**Ahora:** practicante en la OEFA (Coordinación de Residuos Sólidos), donde digitalicé el trabajo de campo de los supervisores.

---

## Proyectos destacados

### 🗺️ Sistema digital de fichas de campo · OEFA
*Código institucional, no público.* · 📄 **[Leer el caso de estudio](https://github.com/leonardovelezdevilla/caso-fichas-de-campo)**

- **Problema:** los supervisores llenaban a mano las fichas de **1 080 áreas degradadas por residuos municipales** y **1 130 por residuos de construcción y demolición**, y luego otro equipo las digitaba.
- **Solución:** dos **apps web progresivas (PWA)** que funcionan en celular y sin internet, con mapa, GPS y **validación en tiempo real** de coordenadas contra capas de SERNANP (áreas naturales protegidas), ANA (faja marginal) y Ministerio de Cultura (zonas arqueológicas). Cada ficha genera su Word y PDF institucional y llega a un **panel de revisión** con acceso restringido, donde se observa o se da conformidad.
- **Calidad:** medición del tiempo de cada ficha, pruebas simuladas, revisión del código con agentes de IA separados y despliegue por versiones documentadas.
- **Resultado:** la revisión de cada ficha bajó de **~1 hora (estimación del área) a una mediana de 5 minutos (‑92 %)**, medida primero con cronómetro y ahora por el propio panel; más de 230 fichas reales recibidas.
- **Stack:** Google Apps Script · JavaScript · HTML/CSS · Cloudflare Pages · Leaflet · IndexedDB

### ⏱️ Automatización de plazos con INAF · OEFA, Zona 1
*Código institucional, no público.*

Herramienta en Apps Script (unas 3 000 líneas) que sincroniza los reportes del sistema INAF con la hoja de gestión, marca inconsistencias, calcula plazos en días hábiles con feriados, envía alertas por correo y ofrece un tablero de indicadores y un portal para supervisores externos.

### 💰 Sol · finanzas personales
App Android en Flutter para registrar gastos, ingresos y transferencias, con presupuestos por categoría, metas de ahorro, cuentas y tarjetas en soles y dólares, captura de avisos de Yape y del banco, y exportación a Excel. Los datos se guardan en el teléfono, sin login.
- Cálculo de saldos desde un libro de movimientos (*ledger*) como fuente de verdad.
- GitHub Actions compila, prueba, firma el APK y graba un recorrido en emulador.
- *Repositorio privado (uso personal y familiar).*

<img src="img/sol.png" alt="Pantallas de Sol: inicio, movimientos y registro" width="720">

### ⚽ Coyote Bot
*Repositorio privado (datos reales de clientes); disponible para demostración.*
Sistema para una escuela de fútbol con 3 sedes: **bot de WhatsApp**, panel de administración pensado para usuarios no técnicos, página web pública, asistencia con carnet QR, caja, cuotas y encuestas.
- Un solo Worker de **Cloudflare** con base de datos **D1 (SQL)**.
- **Más de 250 pruebas automáticas** con un WhatsApp simulado (`npm test`).

### 💜 [VitaRing](https://github.com/leonardovelezdevilla/vitaring)
Prototipo universitario de anillo inteligente: app **Android** y app **Wear OS** que leen el pulso del Galaxy Watch y lo muestran con un semáforo. GitHub Actions compila los APK en cada cambio.

### 🎥 Atisba · videovigilancia inteligente
*Prototipo privado en desarrollo.* Capa de IA que se instala sobre las cámaras y el DVR que el cliente ya tiene: lectura de placas, alertas al celular y asistente en español con IA local.

---

## Cómo trabajo

- **IA aplicada:** Claude, Gemini y NotebookLM para prototipar, programar, revisar código, analizar datos y documentar.
- **Producto:** levantamiento de requerimientos, trabajo por iteraciones, pruebas antes de cada despliegue.
- **Herramientas:** Apps Script · JavaScript · SQL · Git · GitHub Actions · Vercel · Cloudflare · AppSheet · Figma

📍 Lima, Perú
