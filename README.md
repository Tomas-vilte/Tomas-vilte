# Hola, soy Thomas

Soy backend developer, autodidacta, curioso, y bastante hincha con las buenas prácticas. Me gusta meterme en proyectos donde hay desafíos complejos para resolver, aprender cosas nuevas en el camino y dejar todo más ordenado de lo que estaba.

## Un poco sobre mí

- Contacto: viltetomas2003@gmail.com

- Trabajo principalmente con **Golang**, armando APIs limpias, rápidas y fáciles de mantener. También usé bastante **Python**, sobre todo para tareas relacionadas al manejo de datos, automatizaciones y procesamiento.

- Toqué **Java con Spring Boot** en un proyecto, lo suficiente para entender cómo se estructuran aplicaciones más grandes, aunque hoy mi foco está en Go.

- Me siento cómodo usando **Docker** y tengo experiencia desplegando en **AWS** (EC2, Lambda, S3, DynamoDB). Manejo la infraestructura como código usando **Terraform**.

- Trabajé con **Kafka** y **SQS** para mensajería, y con bases de datos como **MySQL**, **MongoDB** y **DynamoDB**, eligiendo la que mejor se adapte al caso.

- Me enfoco mucho en la observabilidad: uso **OpenTelemetry Collector**, **Prometheus**, **Grafana** y **Pyroscope** para monitorear y entender qué está pasando en producción.

---

## Lo que estoy haciendo ahora

Actualmente estoy 100% metido en el desarrollo de **Butakero**, un bot de música para Discord escrito en **Go**, que ya está en producción y siendo usado por más de **500 servidores** (guilds).

El bot tiene una arquitectura modular orientada a la performance, desplegada en **AWS sobre instancias EC2**. Gestiono toda la infraestructura mediante **Terraform**.

Uso **DynamoDB** como base de datos principal para la persistencia de configuraciones y metadata, **OpenSearch** para funcionalidades de búsqueda y **AWS Lambda** para tareas auxiliares de sincronización. Los archivos de audio y assets los manejo en **S3**.

Todo el stack está monitoreado con **OpenTelemetry**, **Grafana** y **CloudWatch**, lo que me permite tener trazabilidad completa de los requests.

Sigo trabajando en nuevas features, mejoras de rendimiento, y todo lo relacionado al crecimiento del bot (incluyendo membresías premium y publicación en [top.gg](https://top.gg/bot/987850036866084974)).

## ¿Querés probarlo?

Podés ver el bot funcionando ahora mismo sin instalar nada:
1. **Unite al servidor de prueba/soporte:** [Discord de la comunidad](https://discord.gg/9hNhgnC5Ue)
2. Andá al canal de música y tirá un comando (ej: `/play`).

Si preferís invitarlo a tu propio servidor o ver las estadísticas públicas:
- **Ver en Top.gg:** [Top.gg](https://top.gg/bot/987850036866084974)

---

## Proyectos destacados

**Butakero Music Bot**
Bot de música para Discord con más de 500 guilds activas. Escrito en Go, desplegado en AWS EC2.
Usa DynamoDB, OpenSearch, Lambda, S3, y tiene un stack completo de observabilidad.
Implementé un pipeline de audio propio optimizado para concurrencia.

---

## Cómo trabajo

- Me gusta dejar el código mejor de lo que lo encontré.
- Prefiero lo simple y mantenible antes que lo complejo.
- Valoro la comunicación clara en el equipo tanto como el código bien hecho.

---

## En qué estoy metido ahora

- Diseñando y manteniendo sistemas reales en producción.
- Aprendiendo más sobre profiling y performance en Go.
- Explorando nuevas formas de optimizar costos y latencia en AWS.

---

### ¿Querés contactarme?

- [LinkedIn](https://www.linkedin.com/in/thomas-ezequiel-vilte-762276217/)  
- **Mail:** viltetomas2003@gmail.com 

---

## Tecnologías y herramientas

- **Lenguajes:** Golang, Python, Java.
- **Frameworks:** Gin, (Spring Boot en un proyecto puntual).
- **Infra y DevOps:** AWS (EC2, Lambda, S3, DynamoDB), Terraform, Docker.
- **Bases de datos:** DynamoDB, MySQL, MongoDB, Redis.
- **Mensajería y eventos:** Kafka, SQS.
- **Búsqueda:** OpenSearch.
- **Observabilidad:** Prometheus, Grafana, CloudWatch, OpenTelemetry Collector, Pyroscope.
- **Otros:** Git, GitHub Actions, CI/CD, testing, Linux.
