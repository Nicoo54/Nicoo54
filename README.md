<div align="center">

# Nicolás Bernardini

**Estudiante de Ingeniería en Sistemas de Información · Universidad Nacional del Sur**

Desarrollo aplicaciones web y móviles con foco en calidad, datos y en entender el problema que cada producto resuelve

📍 Bahía Blanca, Argentina

[![Email](https://img.shields.io/badge/Email-nicolasbernardini54@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:nicolasbernardini54@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nicolás_Bernardini-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nicolas-bernardini-628b9b449/)

</div>

---

> Proyectos académicos (UNS) y desarrollos reales.

## Proyectos destacados

### 1. Marketplace de perfumes + Analytics Dashboard

Ecosistema de aplicaciones con arquitectura de microservicios, desarrollado en un equipo de 5 personas para la materia Ingeniería de Aplicaciones Web.

**Stack:** Next.js · TypeScript · PostgreSQL · Prisma · Clerk · Mercado Pago (sandbox) · Vercel

**Mi parte**

| Componente | Descripción |
|---|---|
| **Buyer App** | Registro e inicio de sesión, catálogo, carrito, historial de compras, panel de administración con gráficos, pagos con Mercado Pago (sandbox) y resumen automático de reseñas con IA. |
| **Control Plane** | Panel de superadministración. Desarrollo individual. |
| **Analytics Dashboard** | Desarrollo individual. Ingresos totales y por mes, ticket promedio, tasa de conversión, usuarios activos, calificación promedio y estado de las órdenes de los últimos 30 días, con filtros por rango de fechas. <!-- TODO: indicar cuántos indicadores son en total --> |

**Enlaces**

[![Demo Analytics Dashboard](https://img.shields.io/badge/Demo-Analytics_Dashboard-2ea44f?style=flat-square&logo=vercel&logoColor=white)](https://perfume-libre-analytics.vercel.app/general)
[![Demo Buyer App](https://img.shields.io/badge/Demo-Buyer_App-2ea44f?style=flat-square&logo=vercel&logoColor=white)](https://REEMPLAZAR-POR-DOMINIO-PRODUCCION.vercel.app/)
<!-- TODO: reemplazar link de Buyer App por el de producción (sin git-develop) y descomentar video cuando esté -->
<!-- [![Video](https://img.shields.io/badge/Video-2_min-FF0000?style=flat-square&logo=youtube&logoColor=white)](LINK) -->

**Usuarios de prueba** (código de verificación: `424242`)

| Rol | Usuario | Contraseña |
|---|---|---|
| Administrador | `admin+clerk_test@iaw.com` | `iawuser#` |
| Comprador | `buyer+clerk_test@iaw.com` | `iawuser#` |


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

**Stack:** Flutter · Dart · SQL (Almacenamiento local)


**Lógica y funcionalidades:**
* **Modelo jerárquico:** Organización por *Cliente → Campo → Lote (hectáreas) → Carga* (kilos, destino, fecha y chofer), calculando en tiempo real kilos totales, hectáreas trabajadas y rinde (kg/ha).
* **Arquitectura Offline-First:** Persistencia local para operar en zonas rurales sin señal y agrupamiento consistente de datos.
* **Recálculo retroactivo:** Edición de hectáreas o kilos con actualización automática de los rindes de toda la campaña.
* **Reportes de negocio:** Exportación directa a Excel y PDF filtrable por fecha, cliente, campo o camión.

**Estado y evolución:** Prototipo funcional validado en entorno de prueba. El desafío técnico principal fue diseñar la persistencia *offline* sin pérdida ni duplicación de registros. El próximo paso es integrar una plataforma web para seguimiento en tiempo real.

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

Plataforma que conecta a personas que necesitan enviar paquetes con conductores independientes. Proyecto de Arquitectura y Diseño de Sistemas (UNS), en equipo de 4 personas, con foco en el diseño y la documentación de la arquitectura.

**Stack:** Next.js · TypeScript · PostgreSQL · Prisma · Clerk · Vercel

**Mi aporte:**
* **Desarrollo Frontend:** Implementación completa de la interfaz, navegación y simulación de conductores en movimiento.
* **Arquitectura y Documentación:** Relevamiento de requerimientos funcionales/no funcionales, modelo de dominio y de datos, diagramas C4 (contexto, contenedores y componentes), especificación de APIs y registro de decisiones de arquitectura (ADRs).

**Decisiones clave:** Monolito en capas · *Polling* sobre HTTP en lugar de WebSockets para simplificar infraestructura · PostgreSQL sin capa de caché intermedia · Procesos *batch* automatizados con Vercel Cron.

[![Documentación](https://img.shields.io/badge/Documentación-PDF-B31B1B?style=flat-square&logo=adobeacrobatreader&logoColor=white)](docs/Packeteer/Packeteer_Documentacion.pdf)
[![Video de demo](https://img.shields.io/badge/Video-Demo-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://youtu.be/csrbMWZOqJs)

<details>
<summary><b>Diagrama</b></summary>

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
| **Gestión de un proyecto de software para una aerolínea** | *En curso.* Participé en la elaboración de la documentación de gestión como plan de riesgos, WBS, métricas de seguimiento y criterios de éxito, priorización de requerimientos y planificación en sprints. | Gestión de proyectos · UML · ProjectLibre | 📄&nbsp;[Documentación](docs/Aerol%C3%ADnea/documentacion.pdf) |
| **Nonograma** | Desarrollo individual. La lógica de reglas corre en SWI-Prolog y la interfaz en React, comunicados mediante Pengines. | Prolog · React | 🎥&nbsp;[Demo](https://youtu.be/YBS6UOwpd2A) 📄&nbsp;[Informe](docs/Nonograma/Informe.pdf) |
| **Clon de Candy Crush** | Equipo de 4. Diseño orientado a objetos aplicando patrones de diseño para la lógica del tablero, combinaciones y puntajes. | Java | 🎥&nbsp;[Demo](https://youtu.be/OViWHFBxXzg) |


---

## Tecnologías

**Datos, Backend y Arquitectura**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

**Desarrollo Frontend y Mobile**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)

**Otros Lenguajes y Herramientas**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
