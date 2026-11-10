<div align="center">

# Nicolás Bernardini

**Estudiante de Ingeniería en Sistemas de Información · Universidad Nacional del Sur**

Me interesan el análisis de datos, la automatización de procesos y el desarrollo web.

📍 Bahía Blanca, Argentina

[![Email](https://img.shields.io/badge/Email-nicolasbernardini54@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:nicolasbernardini54@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nicolás_Bernardini-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nicolas-bernardini-628b9b449/)

</div>

---

## Contenido

- [Proyectos destacados](#proyectos-destacados)
- [Otros proyectos académicos](#otros-proyectos-académicos)
- [Tecnologías](#tecnologías)
- [Contacto](#contacto)

> Todos los proyectos son académicos (UNS) y utilizan datos de prueba.

---

## Proyectos destacados

### 1. Marketplace de perfumes + Analytics Dashboard

Ecosistema de aplicaciones con arquitectura de microservicios, desarrollado en un equipo de 5 personas para la materia Ingeniería de Aplicaciones Web.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=flat-square&logo=clerk&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Mercado Pago](https://img.shields.io/badge/Mercado_Pago_(sandbox)-009EE3?style=flat-square&logo=mercadopago&logoColor=white)

**Mi parte**

| Componente | Descripción |
|---|---|
| **Buyer App** | Registro e inicio de sesión, catálogo, carrito, historial de compras, panel de administración con gráficos, pagos con Mercado Pago (sandbox) y resumen automático de reseñas con IA. |
| **Control Plane** | Panel de superadministración. Desarrollo individual. |
| **Analytics Dashboard** | Desarrollo individual. Ingresos totales y por mes, ticket promedio, tasa de conversión, usuarios activos, calificación promedio y estado de las órdenes de los últimos 30 días, con filtros por rango de fechas. <!-- TODO: indicar cuántos indicadores son en total --> |

**Enlaces**

[![Demo Analytics Dashboard](https://img.shields.io/badge/Demo-Analytics_Dashboard-2ea44f?style=flat-square&logo=vercel&logoColor=white)](https://perfume-libre-analytics.vercel.app/general)
[![Demo Buyer App](https://img.shields.io/badge/Demo-Buyer_App-2ea44f?style=flat-square&logo=vercel&logoColor=white)](https://buyer-app-git-develop-nicoo54s-projects.vercel.app/)
<!-- TODO: agregar el video de 2 minutos (YouTube "no listado") -->
<!-- [![Video](https://img.shields.io/badge/Video-2_min-FF0000?style=flat-square&logo=youtube&logoColor=white)](LINK) -->

**Usuarios de prueba** (sin datos reales)

| Rol | Usuario | Contraseña |
|---|---|---|
| Administrador | `admin+clerk_test@iaw.com` | `iawuser#` |
| Comprador | `buyer+clerk_test@iaw.com` | `iawuser#` |

> 💡 El código de verificación del correo es `424242`.

<details>
<summary><b>📸 Capturas</b></summary>

<br>

<p align="center">
  <img src="images/marketplace-perfume/marketplace-home.png" alt="Catálogo de productos" width="32%">
  <img src="images/marketplace-admin.png" alt="Panel de administración" width="32%">
  <img src="images/marketplace-perfume/marketplace-analytics/analytics-home.png" alt="Analytics Dashboard" width="32%">
</p>

<p align="center"><sub>Catálogo · Panel de administración · Analytics Dashboard</sub></p>

</details>

---

### 2. App de gestión logística de cosecha

Aplicación móvil que digitaliza el control de la cosecha desde la cabina de la maquinaria. Reemplaza las libretas de papel, calcula la productividad automáticamente y genera reportes para los dueños de los campos. Desarrollo individual a partir de los requerimientos de un contratista rural.

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=databricks&logoColor=white)

**Cómo funciona.** El trabajo se organiza en *Cliente → Campo → Lote (con sus hectáreas) → Carga* (kilos, lugar de descarga, fecha y chofer). El panel resume tres indicadores: total de kilos, hectáreas y rinde (kg/ha).

**Funcionalidades**

- 📴 Carga sin conexión (*offline-first*) para zonas sin señal.
- 🔎 Historial filtrable por fecha, cliente, campo o camión.
- ✏️ Corrección de hectáreas y kilos, con recálculo de los rindes de toda la campaña.
- 📊 Reportes para el cliente en Excel, por lote o por camión.

| | |
|---|---|
| **Desafío principal** | Gestionar las cargas sin conexión y agruparlas correctamente al recuperar la señal. Fue mi primer sistema y lo más difícil del proyecto. |
| **Estado** | Prototipo funcional, no implementado con los operarios. |
| **Próximo paso** | Una web que muestre en tiempo real el avance de cada cliente. |

[![Video de demo](https://img.shields.io/badge/Video-Demo-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://youtube.com/shorts/5DGVj7XVGLY)

<details>
<summary><b>📸 Captura del reporte generado</b></summary>

<br>

<p align="center">
  <img src="images/Cosecha/chosecha-reporte-excel.png" alt="Resumen de cargas" width="60%">
</p>

</details>

---

### 3. Packeteer, plataforma de logística colaborativa

Plataforma que conecta a personas que necesitan enviar paquetes con conductores independientes. Proyecto de Arquitectura y Diseño de Sistemas (UNS), en equipo de 5 personas, con foco en el diseño y la documentación de la arquitectura.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=flat-square&logo=clerk&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

**Mi parte**

- Desarrollo completo del frontend, la simulación del conductor en movimiento y la navegación.
- Participación en la documentación: modelo de dominio, requerimientos funcionales y no funcionales, diagramas de contexto, contenedores y componentes, modelo de datos, diseño de APIs y decisiones arquitectónicas (ADRs).

**Decisiones clave:** monolito en capas · *polling* en lugar de WebSockets · PostgreSQL sin caché · procesos *batch* con Vercel Cron.

[![Documentación](https://img.shields.io/badge/Documentación-PDF-B31B1B?style=flat-square&logo=adobeacrobatreader&logoColor=white)](docs/Packeteer/Packeteer_Documentacion.pdf)
[![Video de demo](https://img.shields.io/badge/Video-Demo-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://youtu.be/csrbMWZOqJs)

<details>
<summary><b>📐 Diagrama</b></summary>

<br>

<p align="center">
  <img src="images/Packeteer/Packeteer-diagrama-componentes.png" alt="Diagrama de componentes de Packeteer" width="80%">
</p>

</details>

---

## Otros proyectos académicos

| Proyecto | Descripción | Tecnologías | Enlaces |
|---|---|---|---|
| **Tracker de bíceps** | Equipo de 4. Seguimiento del brazo en video, cálculo del ángulo del codo y gráficos de las variables en función del tiempo. | Python · OpenCV · MediaPipe · NumPy | 🎥 [Demo](https://youtu.be/kwR4GyDo3C8) 📄&nbsp;[Proyecto](docs/Tracker%20de%20b%C3%ADceps/Proyecto%20de%20fisica%20-%20Curl%20de%20biceps.pdf) |
| **Gestión de un proyecto de software para una aerolínea** | *En curso.* Plan de riesgos, WBS, métricas de seguimiento y criterios de éxito, priorización de requerimientos y planificación en sprints. | Gestión de proyectos · UML · ProjectLibre | 📄&nbsp;[Documentación](docs/Aerol%C3%ADnea/documentacion.pdf) |
| **Nonograma** | Desarrollo individual. La lógica de reglas corre en SWI-Prolog y la interfaz en React, comunicados mediante Pengines. | Prolog · React | 🎥&nbsp;[Demo](https://youtu.be/YBS6UOwpd2A) 📄&nbsp;[Informe](docs/Nonograma/Informe.pdf) |
| **Candy Crush** | Equipo de 4. | Java | 🎥&nbsp;[Demo](https://youtu.be/OViWHFBxXzg) |


---

## Tecnologías

**Datos y backend**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![REST](https://img.shields.io/badge/APIs_REST-009688?style=flat-square)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=flat-square&logo=clerk&logoColor=white)

**Desarrollo**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
<!-- TODO: si usás TypeScript, agregá: ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) -->
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Prolog](https://img.shields.io/badge/Prolog-E61B23?style=flat-square)

**Herramientas**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

---

## Contacto

¿Querés charlar sobre algún proyecto u oportunidad? Escribime:

[![Email](https://img.shields.io/badge/Email-nicolasbernardini54@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:nicolasbernardini54@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nicolás_Bernardini-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nicolas-bernardini-628b9b449/)
