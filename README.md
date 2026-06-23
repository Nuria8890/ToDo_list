# 📝 ToDo List

Aplicación web para gestionar tus tareas diarias de forma sencilla. Crea, busca, completa y elimina ToDos; tus tareas se guardan automáticamente en el navegador gracias a `localStorage`.

🔗 **Demo en vivo:** [https://Nuria8890.github.io/ToDoList](https://Nuria8890.github.io/ToDoList)

---

## ✨ Características

- ✅ Crear nuevas tareas mediante un modal.
- 🔍 Buscar tareas en tiempo real.
- ✔️ Marcar tareas como completadas.
- 🗑️ Eliminar tareas.
- 💾 Persistencia de datos con `localStorage`.
- 📱 Interfaz adaptable y amigable.

---

## 🛠️ Tecnologías

- [React](https://react.dev/) 18
- [Create React App](https://create-react-app.dev/)
- [React Icons](https://react-icons.github.io/react-icons/)
- HTML5, CSS3 y JavaScript (ES6+)

---

## 🚀 Instalación y uso

1. Clona el repositorio:

   ```bash
   git clone https://github.com/Nuria8890/ToDoList.git
   cd ToDoList
   ```

2. Instala las dependencias:

   ```bash
   npm install
   ```

3. Inicia el servidor de desarrollo:

   ```bash
   npm run dev
   ```

4. Abre [http://localhost:3000](http://localhost:3000) en tu navegador.

---

## 📦 Scripts disponibles

| Script         | Descripción                                  |
| -------------- | -------------------------------------------- |
| `npm run dev`  | Inicia la aplicación en modo desarrollo.     |
| `npm run build`| Genera la versión optimizada para producción.|
| `npm run deploy`| Despliega la carpeta `build` con `gh-pages`.|
| `npm run eject`| Expone la configuración de React (irreversible).|

---

## 📂 Estructura del proyecto

```
ToDoList/
├── public/                 # Archivos estáticos
├── src/
│   ├── App/                # Componente raíz y UI principal
│   ├── TodoContext/        # Contexto global y hook de localStorage
│   ├── TodoCounter/        # Contador de tareas completadas
│   ├── TodoSearch/         # Barra de búsqueda
│   ├── TodoList/           # Listado de tareas
│   ├── TodoItem/           # Item individual de una tarea
│   ├── TodoButton/         # Botón para abrir el modal
│   ├── TodoForm/           # Formulario para añadir tareas
│   ├── Modal/              # Componente modal
│   ├── EmptyTodos/         # Estado cuando no hay tareas
│   ├── TodosLoading/       # Estado de carga
│   └── TodosError/         # Estado de error
├── package.json
└── README.md
```

---

## 👩‍💻 Autor

**Nuria** — [@Nuria8890](https://github.com/Nuria8890)

---

> Proyecto personal de práctica con React.
