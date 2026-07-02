# 🎓 Sistema de Gestión de Estudiantes — ITB

Este es un sistema de escritorio de tipo **CRUD** (Crear, Leer, Actualizar y Borrar) desarrollado en Python para la administración de registros de estudiantes. Utiliza una interfaz gráfica interactiva y almacenamiento local persistente.

---

## 🚀 Características

* **Persistencia de datos:** Los registros se guardan localmente en una base de datos relacional sin necesidad de configuraciones complejas.
* **Interfaz Gráfica (GUI):** Diseñada de forma intuitiva utilizando elementos visuales modernos y tablas con barras de desplazamiento.
* **Interactividad con un clic:** Al hacer clic en cualquier estudiante de la tabla, sus datos se cargan automáticamente en los campos para editarlos o eliminarlos de forma ágil.
* **Control de errores:** Validación integrada para evitar campos vacíos y asegurar que las calificaciones sean numéricas.

---

## 🛠️ Tecnologías Utilizadas

* **Python:** Lenguaje de programación principal.
* **Tkinter / ttk:** Biblioteca estándar para el diseño de la interfaz gráfica de usuario y componentes visuales (`Treeview`, `Scrollbar`).
* **SQLite3:** Motor de base de datos ligero integrado en Python que gestiona la persistencia de información en un archivo `.db`.

---

## 📂 Estructura de la Base de Datos

El sistema crea y administra de forma automática una base de datos llamada `estudiantes.db` con la siguiente estructura:

| Campo | Tipo de Dato | Propiedades | Descripción |
| :--- | :--- | :--- | :--- |
| **id** | INTEGER | PRIMARY KEY AUTOINCREMENT | Identificador único del estudiante. |
| **nombre** | TEXT | NOT NULL | Nombre completo del alumno. |
| **carrera** | TEXT | NOT NULL | Carrera que está cursando. |
| **nota** | REAL | NOT NULL | Calificación o nota obtenida. |

---

## 💻 Requisitos e Instalación

### Requisitos Previos
* Python 3.x instalado en tu sistema.
* *Nota: No se requieren librerías de terceros (`pip`), ya que todas forman parte de la librería estándar de Python.*

### Instrucciones de Ejecución
1. Descarga o clona este repositorio:
   ```bash
   git clone [https://github.com/tu-usuario/tu-repositorio.git](https://github.com/tu-usuario/tu-repositorio.git)