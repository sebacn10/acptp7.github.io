## TP7 — Conexión PDO y CRUD

Se utiliza **PDO** para conectar PHP con MySQL y realizar operaciones con consultas preparadas. El CRUD administra evaluaciones:

| Operación | Archivo o función |
|---|---|
| **Crear (Create)** | `Formulario.php`: enviar y guardar una evaluación |
| **Leer (Read)** | `admin/registros.php`: consultar y filtrar registros |
| **Actualizar (Update)** | `admin/editar.php`: modificar observación y estado |
| **Eliminar (Delete)** | `admin/eliminar.php`: eliminación mediante `POST` y comprobación CSRF |

**Listado de registros (Read):**

![Lectura de registros TP7](capturas%20tp7/tp7-read.png)

**Edición de registros (Update):**

![Actualización de registros TP7](capturas%20tp7/tp7-update.png)

**Eliminación protegida (Delete):**

![Eliminación protegida TP7](capturas%20tp7/tp7-delete.png)
