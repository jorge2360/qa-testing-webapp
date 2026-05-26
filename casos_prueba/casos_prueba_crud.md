# Casos de prueba - CRUD de tareas

## CP-004 - Crear tarea correctamente

| Campo | Detalle |
|---|---|
| Módulo | Gestión de tareas |
| Prioridad | Alta |
| Tipo | Funcional |
| Precondición | Usuario autenticado |
| Datos de prueba | título, descripción, prioridad, estado y fecha |
| Pasos | 1. Iniciar sesión. 2. Ir al dashboard. 3. Completar formulario de tarea. 4. Presionar guardar. |
| Resultado esperado | La tarea debe registrarse y mostrarse en el listado. |
| Resultado obtenido | La tarea se registra y muestra en el listado. |
| Estado | Exitoso |

---

## CP-005 - Editar tarea existente

| Campo | Detalle |
|---|---|
| Módulo | Gestión de tareas |
| Prioridad | Alta |
| Tipo | Funcional |
| Precondición | Usuario autenticado y tarea existente |
| Datos de prueba | nueva descripción, prioridad o estado |
| Pasos | 1. Seleccionar una tarea. 2. Presionar editar. 3. Modificar datos. 4. Guardar cambios. |
| Resultado esperado | La tarea debe actualizarse correctamente. |
| Resultado obtenido | La tarea se actualiza correctamente. |
| Estado | Exitoso |

---

## CP-006 - Eliminar tarea

| Campo | Detalle |
|---|---|
| Módulo | Gestión de tareas |
| Prioridad | Alta |
| Tipo | Funcional |
| Precondición | Usuario autenticado y tarea existente |
| Datos de prueba | tarea registrada |
| Pasos | 1. Seleccionar una tarea. 2. Presionar eliminar. 3. Confirmar eliminación. |
| Resultado esperado | La tarea debe eliminarse del listado. |
| Resultado obtenido | La tarea se elimina del listado. |
| Estado | Exitoso |

---

## CP-007 - Búsqueda de tarea

| Campo | Detalle |
|---|---|
| Módulo | Gestión de tareas |
| Prioridad | Media |
| Tipo | Funcional |
| Precondición | Usuario autenticado y tareas registradas |
| Datos de prueba | texto contenido en título o descripción |
| Pasos | 1. Ingresar texto en buscador. 2. Revisar resultados filtrados. |
| Resultado esperado | El sistema debe mostrar únicamente tareas coincidentes. |
| Resultado obtenido | El sistema muestra únicamente tareas coincidentes. |
| Estado | Exitoso |

---

## CP-008 - Filtro por estado y prioridad

| Campo | Detalle |
|---|---|
| Módulo | Gestión de tareas |
| Prioridad | Media |
| Tipo | Funcional |
| Precondición | Usuario autenticado y tareas registradas |
| Datos de prueba | estado pendiente, completada, prioridad alta, media o baja |
| Pasos | 1. Seleccionar filtro de estado. 2. Seleccionar filtro de prioridad. 3. Revisar resultados. |
| Resultado esperado | El sistema debe mostrar tareas que coincidan con los filtros aplicados. |
| Resultado obtenido | El sistema muestra tareas que coinciden con los filtros aplicados. |
| Estado | Exitoso |