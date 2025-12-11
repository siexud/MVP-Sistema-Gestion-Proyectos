# 📘 MVP – Sistema de Gestión de Proyectos  
### SIEXUD · Versión MVP 2025

Este repositorio contiene la información pública del **MVP del Sistema de Gestión de Proyectos**, un componente inicial del ecosistema digital desarrollado para la **Oficina de Extensión de la Universidad Distrital Francisco José de Caldas**.

El objetivo principal del sistema es facilitar el proceso de **registro, evaluación, aprobación y documentación de proyectos de extensión**, sirviendo como base para la arquitectura final del sistema **SIEXUD 2025**.

---

## 🚀 Descripción General

El **MVP-Sistema-Gestion-Proyectos** utiliza una arquitectura **basada en microservicios**, contenedores **Docker** y un **API Gateway con NGINX**, permitiendo:

- ✔ Modularidad  
- ✔ Escalabilidad horizontal  
- ✔ Despliegues consistentes  
- ✔ Integración futura con el ecosistema SIEXUD  
- ✔ Mantenimiento independiente por componente  

Este MVP valida los flujos principales y sienta las bases del sistema completo.

---

## 🏗️ Arquitectura General

El sistema está compuesto por varios microservicios, entre ellos:

- **Microservicio de Gestión de Proyectos**
- **Microservicio de Autenticación**
- **Front-End basado en plantillas EJS**
- **NGINX como API Gateway**
- **Servicios complementarios (en desarrollo)**

Cada servicio opera dentro de un contenedor Docker y se orquesta utilizando `docker-compose`.

---

## 🧱 Tecnologías Utilizadas

- **Node.js + Express** – Backend modular por microservicios  
- **NGINX** – Proxy inverso y API Gateway  
- **Docker / Docker Compose** – Contenedorización y despliegue  
- **Arquitectura basada en microservicios**  
- **Plantillas EJS / HTML dinámico** para la capa de interfaz  
- **Base de datos relacional** (según configuración de entorno)

---

## 📂 Estructura General del Proyecto

```bash
MVP-Sistema-Gestion-Proyectos/
├── docker-compose.yml # Orquestación de microservicios
├── nginx/ # Configuración del Gateway
├── servicios/ # Microservicios del sistema
│ ├── auth/ # Autenticación
│ ├── proyectos/ # Gestión de proyectos
│ └── ... # Futuras extensiones
└── docs/ # Documentación pública
```


> Esta estructura refleja únicamente la organización general.  
> El código detallado reside en el repositorio privado correspondiente.

---

## 🎯 Objetivo del MVP

Este MVP fue diseñado para validar:

- ✔ La arquitectura modular del SIEXUD  
- ✔ La comunicación entre microservicios  
- ✔ El flujo central de registro y aprobación de proyectos  
- ✔ El despliegue mediante Docker  
- ✔ La base tecnológica que soportará la versión completa  

Representa la versión mínima funcional sobre la cual crecerá el sistema institucional.

---

## 🔐 Repositorio Privado

La versión completa —incluyendo todo el código fuente, la integración completa de microservicios, configuraciones avanzadas y la lógica final del sistema— se encuentra en un repositorio privado.

Para solicitar acceso puede comunicarse con:

coordinacionTIidexud@udistrital.edu.co

webmasteridexud@udistrital.edu.co

softwareidexud@udistrital.edu.co

📧 **Equipo DevOps – Oficina de Extensión UD**  

---

## 🤝 Contacto

**Oficina de Extensión – Universidad Distrital Francisco José de Caldas**  
Equipo de Desarrollo & DevOps  
Si deseas colaborar, aportar ideas o solicitar acceso, puedes comunicarte a través de los canales institucionales.

---

## 🎉 Gracias por tu interés en el proyecto

Este MVP sienta las bases para una plataforma moderna, robusta y alineada con las necesidades de transformación digital de la universidad.

