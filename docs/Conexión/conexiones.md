---
id: administrar-conexiones
title: Administración de Conexiones
sidebar_label: Conexiones
---

# Administración de Conexiones

## ❓ Pregunta principal  
¿Cómo puedo crear, editar y administrar las conexiones en MaxPoint?  

## ✅ Respuesta clara y breve  
En el módulo **Conexiones** de MaxPoint puedes gestionar los enlaces entre servidores, adaptadores y repositorios previamente creados. Desde aquí podrás **crear nuevas conexiones**, **visualizar las existentes**, **activarlas o inactivarlas** y **editar su configuración** para garantizar una correcta integración de datos en los procesos de carga.  

---

## 📋 Detalles paso a paso  

### 🔹 Acceso a la sección Conexiones  
1. En el menú lateral, dirígete a **CONFIGURADOR**.  
2. Selecciona **Integración > Conexión > Conexiones**.  
3. Se mostrará la lista de conexiones existentes.  

### 🔹 Crear una conexión  
1. Haz clic en el botón **Crear conexión**.  
2. Ingresa la información requerida:  
   - Nombre representativo.  
   - Servidor (selección de lista desplegable).  
   - Adaptador (selección de lista desplegable con opción de búsqueda).  
   - Repositorio (selección de lista desplegable con opción de búsqueda).  
   - Descripción (opcional).  
3. Haz clic en **Guardar conexión**.  
4. El sistema confirmará con el mensaje: ✅ *Conexión creada correctamente*.  

### 🔹 Editar una conexión  
1. En la lista, localiza la conexión deseada.  
2. Haz clic en el ícono de **editar (✏️)**.  
3. Modifica los datos necesarios (nombre, servidor, adaptador, repositorio o descripción).  
4. Haz clic en **Actualizar conexión**.  
5. El sistema mostrará la confirmación: ✅ *Actualizado correctamente*.  

### 🔹 Activar o inactivar una conexión  
1. Ubica la conexión en la lista.  
2. Haz clic en el ícono correspondiente en la columna **Acciones**.  
3. Confirma en el cuadro de diálogo: *¿Está seguro que desea activar/inactivar?*  
4. La conexión cambiará de estado y el sistema confirmará la acción.  

:::important  
No es posible inactivar una conexión vinculada a un proceso activo.  
:::  

---

## 📊 Campos/Parámetros importantes  

- **Código** → Identificador único de la conexión (Ejemplo: C001).  
- **Nombre** → Nombre asignado por el usuario.  
- **Servidor** → Dirección del servidor asociado.  
- **Adaptador** → Tipo de base de datos o servicio (ej: SQL Server, MariaDB, MongoDB).  
- **Repositorio** → Repositorio o base de datos vinculada.  
- **Estado** → Activo / Inactivo.  
- **Acciones** → Opciones disponibles: editar, ver detalles, activar/inactivar.  

---

## 💡 Notas y consejos  

- Usa la barra de búsqueda para filtrar conexiones rápidamente por **nombre**.  
- Ajusta la cantidad de registros visibles en la tabla (10, 20, 50 o 100).  
- Antes de crear una conexión, asegúrate de tener configurados **servidores, adaptadores y repositorios**.  

---

## 🔄 Acciones disponibles  

- **Crear conexión** → Registrar una nueva conexión.  
- **Editar conexión** → Modificar datos de una conexión existente.  
- **Ver detalles** → Consultar información de la conexión.  
- **Activar conexión** → Habilitar una conexión previamente inactiva.  
- **Inactivar conexión** → Deshabilitar una conexión (si no está vinculada a procesos).  

---

## 🔗 Ejemplo de consulta en lenguaje natural  

- **Usuario**: "¿Cómo creo una nueva conexión en MaxPoint?"  
- **IA responde**: "Ingresa a **Configurador > Integración > Conexión > Conexiones**, haz clic en **Crear conexión**, completa los campos requeridos (nombre, servidor, adaptador y repositorio) y guarda la conexión. El sistema confirmará la creación."  
