# Nicolás Bernardini

Estudiante de Ingeniería en Sistemas de Información (Universidad Nacional del Sur), interesado en análisis de datos, automatización de procesos y desarrollo web.

📍 Bahía Blanca, Argentina · ✉️ [nicolasbernardini54@gmail.com](mailto:nicolasbernardini54@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/nicolas-bernardini-628b9b449/)  

## Proyectos destacados

> Todos son proyectos académicos de la UNS, con datos de prueba.

### 1. Marketplace de perfumes + Analytics Dashboard

Ecosistema de aplicaciones con arquitectura de microservicios, desarrollado en equipo de 5 personas para Ingeniería de Aplicaciones Web.

**Mi parte**
- **Buyer App:** registro e inicio de sesión, catálogo, carrito, historial de compras, panel de administración con gráficos, pagos con Mercado Pago (sandbox) y resumen automático de reseñas con IA.
- **Control Plane:** panel de superadministración, desarrollado en forma individual.
- **Analytics Dashboard:** desarrollado en forma individual. Incluye ingresos totales y por mes, ticket promedio, tasa de conversión, usuarios activos, calificación promedio y estado de órdenes de los últimos 30 días, con filtros por rango de fechas. [Si querés, agregá cuántos indicadores son en total.]

**Stack:** Next.js · PostgreSQL · Prisma · Clerk · Vercel · Mercado Pago (sandbox)

**Links**
- 🔗 [Demo en vivo (Analytics Dashboard)](https://perfume-libre-analytics.vercel.app/general)
- 🔗 [Demo en vivo (Buyer App)](https://buyer-app-git-develop-nicoo54s-projects.vercel.app/)
- 🎥 Video de 2 minutos: [link de YouTube "no listado"]

**Usuarios de prueba** (sin datos reales)
| Rol | Usuario | Contraseña |
|---|---|---|
| Administrador | admin+clerk_test@iaw.com | iawuser# |
| Comprador | buyer+clerk_test@iaw.com | iawuser# |

> El codigo de correo es 424242.

<details>
<summary><b>Capturas</b></summary>

![Catálogo de productos](images/marketplace-perfume/marketplace-home.png)
![Panel de administración](images/marketplace-admin.png)
![Analytics Dashboard](images/marketplace-perfume/marketplace-analytics/analytics-home.png)

</details>
---

### 2. App de gestión logística de cosecha

Aplicación móvil que digitaliza el control de la cosecha desde la cabina de la maquinaria. Reemplaza las libretas de papel, calcula la productividad automáticamente y genera reportes para los dueños de los campos. Desarrollada en forma individual a partir de los requerimientos de un contratista rural.

**Cómo funciona:** el trabajo se organiza en Cliente → Campo → Lote (con sus hectáreas) → Carga (kilos, lugar de descarga, fecha y chofer). El panel resume tres indicadores: total de kilos, hectáreas y rinde (kg/ha).

**Funcionalidades**
- Carga sin conexión (offline-first) para zonas sin señal.
- Historial filtrable por fecha, cliente, campo o camión.
- Corrección de hectáreas y kilos, con recálculo de los rindes de toda la campaña.
- Reportes para el cliente en Excel, por lote o por camión.

**Stack:** Flutter · Dart · SQL

**Desafío principal:** gestionar las cargas sin conexión y agruparlas correctamente al recuperar la señal. Fue mi primer sistema y lo más difícil del proyecto.

**Estado:** prototipo funcional, no implementado con los operarios. **Próximo paso:** una web que muestre en tiempo real el avance de cada cliente.

<details>
<summary><b>Captura y video</b></summary>

![Resumen de cargas](images/Cosecha/chosecha-reporte-excel.png)
🎥 [Video de demo](https://youtube.com/shorts/5DGVj7XVGLY)

</details>

---

### 3. Packeteer, plataforma de logística colaborativa

Plataforma que conecta a personas que necesitan enviar paquetes con conductores independientes. Proyecto de Arquitectura y Diseño de Sistemas (UNS), en equipo de 5 personas. El foco estuvo en el diseño y la documentación de la arquitectura.

**Mi parte**
- Desarrollo completo del frontend, la simulación del conductor en movimiento y la navegación.
- Participación en la documentación: modelo de dominio, requerimientos funcionales y no funcionales, diagramas de contexto, contenedores y componentes, modelo de datos, diseño de APIs y decisiones arquitectónicas (ADRs).
**Decisiones clave:** monolito en capas, polling en lugar de WebSockets, PostgreSQL sin caché y procesos batch con Vercel Cron.
**Stack:** Next.js · PostgreSQL · Prisma · Clerk · Vercel

<details>
<summary><b>Capturas y diagramas</b></summary>
  
[Diagrama de contenedores](images/Packeteer/Packeteer-diagrama-componentes.png)
[📄 Documentación completa (PDF)](docs/Packeteer/Packeteer_Documentacion.pdf)
[🎥 Video de la demo](https://youtu.be/csrbMWZOqJs)

</details>
---

---

## Otros proyectos académicos

- **Tracker de bíceps** (equipo de 4; Python, OpenCV, MediaPipe, NumPy): seguimiento del brazo en video, cálculo del ángulo del codo y gráficos de las variables en función del tiempo. [🎥 Video de la demo](https://youtu.be/kwR4GyDo3C8) [📄 Proyecto)](docs/Tracker%20de%20b%C3%ADceps/Proyecto%20de%20fisica%20-%20Curl%20de%20biceps.pdf)
- **Gestión de un proyecto de software para una aerolínea** (en curso): plan de riesgos, WBS, métricas de seguimiento y criterios de éxito, priorización de requerimientos y planificación en sprints. 
- **Nonograma**: Juego de nonogramas desarrollado en forma individual. La lógica de reglas corre en SWI-Prolog y la interfaz en React, comunicados mediante Pengines. [🎥 Video de la demo](https://youtu.be/YBS6UOwpd2A) [📄 Documentación completa (PDF)](docs/Nonograma/Informe.pdf)
- **Candy Crush** (equipo de 4; Java): [🎥 Video de la demo](https://youtu.be/OViWHFBxXzg)

---

## Tecnologías

- **Datos y backend:** SQL (PostgreSQL), Prisma, APIs REST, Clerk
- **Desarrollo:** JavaScript [/ TypeScript], Next.js, React, Java, Python, Dart/Flutter, Prolog
- **Herramientas:** Git, GitHub, Vercel

## Contacto

✉️ [nicolasbernardini54@gmail.com](mailto:nicolasbernardini54@gmail.com)
