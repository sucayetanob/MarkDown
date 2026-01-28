## Flujo Operativo Actual Implementado

| # | Etapa del flujo | Rol responsable | Descripción de la operación | Tipo de acción |
|--|-----------------|-----------------|-----------------------------|----------------|
| 1 | Registro de solicitud ciudadana | Ciudadano | El ciudadano registra su solicitud en el sistema; al enviar la solicitud se genera automáticamente su usuario con la información proporcionada | Manual |
| 2 | Validación inicial | Funcionario SE | Revisa la información y documentación de la solicitud; puede validar, rechazar o enviar la solicitud a corrección con retroalimentación al ciudadano | Manual |
| 3 | Asignación de solicitud | Supervisor de asignación (Organismo Auditor) | Asigna la solicitud validada a un auditor y cambia el estatus a *Solicitud asignada* | Manual |
| 4 | Agenda de cita | Auditor | El auditor agenda la cita de auditoría dentro del sistema | Manual |
| 5 | Confirmación de cita | Ciudadano | El ciudadano confirma la cita mediante el enlace recibido por correo electrónico | Manual |
| 6 | Auditoría en proceso | Sistema | En la fecha y hora exactas de la cita confirmada, el sistema cambia automáticamente el estatus de la solicitud a *Auditoría en proceso* | Automática |
| 7 | Conclusión de auditoría | Auditor | El auditor concluye la auditoría mediante un botón; el sistema cambia el estatus a *Auditoría concluida* | Manual |
