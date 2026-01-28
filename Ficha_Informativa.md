# TARJETA INFORMATIVA  
## Estado actual del Sistema Marca Guanajuato

**Elaboró:** Stalyn Uriel Cayetano Blanco  
**Fecha:** 28 de Enero 2026  

---

## Contexto General

El **Sistema Marca Guanajuato** es la plataforma que soporta el trámite del **Distintivo Marca Guanajuato**, el cual es de alto impacto para el sector productivo del estado.

Previo a la implementación del sistema actual, el proceso se realizaba de manera principalmente manual y la plataforma existente únicamente permitía:

- El registro inicial de solicitudes.

No existía trazabilidad del proceso, control de roles ni una participación estructurada de las áreas responsables y organismos auditores.

---

## Alcance del sistema implementado

El sistema actualmente **se encuentra implementado y en operación**, cubriendo el flujo operativo definido por el área responsable del trámite.

Las funcionalidades desarrolladas e implementadas incluyen:

- Registro de solicitud por parte del ciudadano.
- Generación automática de usuario ciudadano.
- Portal Ciudadano para consulta de estatus y atención a correcciones.
- Validación inicial de solicitudes por la Secretaría de Economía.
- Retroalimentación y envío a corrección cuando aplica.
- Asignación de solicitudes a organismos auditores.
- Asignación de auditor a cada solicitud.
- Agenda de citas de auditoría.
- Confirmación de cita por parte del ciudadano.
- Cambio automático de estatus a *Auditoría en proceso* en la fecha programada.
- Conclusión de auditoría por parte del auditor.
- Bitácora de seguimiento y trazabilidad por estatus.
- Notificaciones automáticas durante el flujo.
- **Monitor general de solicitudes**, que permite visualizar el total de avance de todas las solicitudes de acuerdo con su estatus dentro del flujo operativo.
- **Dashboard de validaciones**, que muestra de forma gráfica las solicitudes validadas por el Funcionario de la Secretaría de Economía, permitiendo el monitoreo del avance y carga operativa.

Este alcance corresponde al **flujo operativo actualmente utilizado por las áreas involucradas**.

---
## Seguridad y Arquitectura del Sistema

El portal cuenta con un esquema de seguridad basado en **ASP.NET Identity**, desarrollado en **Razor Pages**.

La solución utiliza **SQL Server** como motor de base de datos y contempla el uso de **dos bases de datos independientes**:
- Una destinada exclusivamente al **almacenamiento y gestión de usuarios, roles y credenciales**.
- Otra orientada al **almacenamiento de la información operativa del sistema**, garantizando la separación de responsabilidades y un mayor control de la información.

El sistema se encuentra **alojado en la infraestructura tecnológica de la Secretaría de Economía**, cumpliendo con los lineamientos institucionales de seguridad y operación.

Asimismo, el sistema implementa **sesiones con tiempo de caducidad**, reforzando el control de acceso.

Cada pantalla y funcionalidad opera con base en **roles y permisos predefinidos**, asegurando que los usuarios únicamente puedan acceder a las acciones y datos que les corresponden de acuerdo con su perfil.

---
## Validación institucional

Durante el desarrollo y puesta en operación del sistema:

- El flujo fue definido por el área responsable del trámite.
- Las funcionalidades fueron revisadas mediante historias de usuario, sesiones de trabajo y una presentación institucional realizada el **22 de abril del 2025**, en la cual se determinó el **lanzamiento oficial  de la plataforma el 01 de mayo del 2025**.
- No se cuenta con actas formales de aceptación firmadas; sin embargo, el sistema fue autorizado para su uso y se encuentra en operación.

---

## Consideraciones finales

El **Sistema Marca Guanajuato**:

- Se encuentra **implementado, operativo y en uso**.
- Digitaliza el flujo definido por las áreas responsables.
- Proporciona trazabilidad, control de roles y seguimiento del trámite.

Cualquier funcionalidad adicional o extensión del proceso corresponde a **etapas posteriores de fortalecimiento**, las cuales **no forman parte del alcance actualmente implementado**.
