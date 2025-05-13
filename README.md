# m-todos-de-arreglos
# ✅ Desafío 5 - Todo List

## 📋 Descripción

Este desafío consiste en crear una aplicación de tipo **Todo List**, que permita al usuario agregar, eliminar y marcar tareas como completadas. Además, el sistema debe llevar un **conteo en tiempo real** del total de tareas y cuántas han sido realizadas.

Todo esto se gestiona con un **arreglo de objetos** en JavaScript, y se manipula el DOM para actualizar la vista dinámicamente.

---

## 🧱 Estructura del proyecto

javascript-metodos-arreglos/
├── index.html # Maquetado de la interfaz principal
├── assets/
│ ├── css/
│ │ └── style.css # Estilos básicos de la aplicación
│ └── js/
│ └── scrits.js # Lógica JavaScript de la Todo List

---

## 🚀 Funcionalidades implementadas

### ✅ Agregar tareas
- El usuario puede ingresar una descripción en un input.
- Al hacer clic en "Agregar", la tarea se guarda en un arreglo de objetos y se muestra en pantalla.

### 🗑️ Eliminar tareas
- Cada tarea incluye un botón de eliminación.
- Al hacer clic, la tarea se elimina del arreglo y se actualiza la vista.

### 🔄 Marcar como completada
- Cada tarea incluye un checkbox para indicar si está realizada.
- Al hacer clic, se cambia su estado (`completada: true/false`) y se aplica un estilo al texto.

### 🔢 Contador dinámico
- Se muestra:
  - Total de tareas
  - Total de tareas completadas
- Estos valores se actualizan automáticamente al modificar el arreglo.

### 📝 Tareas iniciales
- Se inicializa el arreglo con **al menos 3 tareas predefinidas**, como se exige en el desafío.

---

## 💡 Lógica del arreglo

Cada tarea se representa como un objeto en el arreglo `tareas`, con la siguiente estructura:

```javascript
{
  id: 1,
  descripcion: "Estudiar JavaScript",
  completada: false
}

## 🧑‍💻 Tecnologías usadas
HTML5

CSS3

JavaScript (ES6)

DOM API

## 📌 Cómo usar

git clone https://github.com/Andreadavj/javascript-metodos-arreglos


## 👩‍🎓 Aprendizajes aplicados
Manejo de arreglos de objetos

Manipulación del DOM

Creación dinámica de elementos HTML

Uso de eventos (onclick)

Condicionales y actualización del estado

## 👩‍💻 Autora
Doris Valverde Jara
Frontend Developer | Desafío Latam
🔗 GitHub

