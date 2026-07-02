# 🎓 Sistema de Gestión de Estudiantes

Aplicación de escritorio desarrollada en **Python** utilizando **Tkinter** para la interfaz gráfica y **SQLite** como base de datos. Permite administrar estudiantes mediante las operaciones básicas de un CRUD (Crear, Leer, Actualizar y Eliminar).

---

## 📌 Características

- ➕ Agregar estudiantes.
- 📋 Mostrar todos los registros.
- ✏️ Editar información de un estudiante.
- 🗑️ Eliminar estudiantes con confirmación.
- 🔄 Actualizar la tabla de registros.
- 💾 Base de datos SQLite creada automáticamente.
- 🖥️ Interfaz gráfica desarrollada con Tkinter.

---

## 🛠️ Tecnologías utilizadas

- Python 3
- Tkinter
- SQLite3

---

## 📂 Estructura del proyecto

```text
Sistema-Estudiantes/
│
├── main.py              # Código principal
├── estudiantes.db       # Base de datos (se crea automáticamente)
└── README.md
```

---

## ▶️ Cómo ejecutar el proyecto

### 1. Clonar el repositorio

```bash
git clone https://github.com/TU-USUARIO/TU-REPOSITORIO.git
```

### 2. Entrar a la carpeta

```bash
cd TU-REPOSITORIO
```

### 3. Ejecutar el programa

```bash
python main.py
```

Si tienes varias versiones de Python:

```bash
python3 main.py
```

---

## 🗄️ Base de datos

El programa crea automáticamente una base de datos llamada:

```
estudiantes.db
```

La tabla utilizada es:

| Campo | Tipo |
|--------|------|
| id | INTEGER |
| nombre | TEXT |
| carrera | TEXT |
| nota | REAL |

---

## 📸 Funcionalidades

### Agregar estudiante

Permite registrar un estudiante ingresando:

- Nombre
- Carrera
- Nota

---

### Editar estudiante

Selecciona un registro de la tabla y modifica sus datos.

---

### Eliminar estudiante

Permite eliminar un registro mostrando un mensaje de confirmación antes de borrar la información.

---

### Actualizar

Recarga la información almacenada en la base de datos.

---

## 📖 Operaciones CRUD

| Operación | Descripción |
|-----------|-------------|
| Create | Agregar un nuevo estudiante |
| Read | Mostrar todos los estudiantes |
| Update | Modificar un estudiante |
| Delete | Eliminar un estudiante |

---

## 📷 Interfaz

La aplicación cuenta con:

- Campos de texto para ingresar datos.
- Botones para cada operación del CRUD.
- Tabla (Treeview) para visualizar los registros.
- Barra de desplazamiento vertical.

---

## 🚀 Mejoras futuras

- Buscar estudiantes por nombre.
- Ordenar registros.
- Exportar a Excel o PDF.
- Validar rangos de notas.
- Agregar inicio de sesión.

---

## 👨‍💻 Autor

Desarrollado como práctica académica utilizando **Python**, **Tkinter** y **SQLite**.

---

## 📄 Licencia

Este proyecto es de uso académico y educativo.
