# RepasoAngular

## 📁 Estructura del Proyecto

La estructura principal del proyecto es la siguiente:

```
RepasoAngular/
│
├── angular.json
├── package.json
├── tsconfig.json
├── tsconfig.app.json
├── tsconfig.spec.json
├── .editorconfig
├── .gitignore
├── README.md
├── public/
│   └── favicon.ico
├── docs/
│   ├── 1dataBinding.pdf
│   ├── 2formulariosAngular.pdf
│   └── 3Práctica_empleados_clase3_Formulario.pdf
├── src/
│   ├── index.html
│   ├── main.ts
│   ├── styles.css
│   ├── data/
│   │   └── plantilla.json
│   └── app/
│       ├── app.component.ts
│       ├── app.component.html
│       ├── app.component.css
│       ├── app.component.spec.ts
│       ├── app.config.ts
│       ├── app.routes.ts
│       ├── empleados.service.ts
│       ├── empleados.service.spec.ts
│       ├── models/
│       │   └── personal.ts
│       └── componentes/
│           └── listar-empleados/
│               ├── listar-empleados.component.ts
│               ├── listar-empleados.component.html
│               ├── listar-empleados.component.css
│               └── listar-empleados.component.spec.ts
└── .vscode/
    ├── extensions.json
    ├── launch.json
    └── tasks.json
```

---

## 🎯 Clase#3 Objetivos y Tarea

<details>
<summary>Haz clic para ver los objetivos y la tarea</summary>

### Objetivos del Módulo

- Generar un componente `agregar-empleado`.
- Implementar la lógica del componente `agregar-empleado` (`.ts`).
- Implementar el formulario por template en el componente `agregar-empleado`.
- Probar que el formulario agrega registros tanto en la **vista** como en el **localStorage**.

### Tarea personal

> En tu proyecto de doctores:

- Genera un componente `agregar-doctor`.
- Implementa la lógica del componente `agregar-doctor` (`.ts`).
- Crea el formulario por template en el componente `agregar-doctor`.
- Asegúrate de que el formulario agrega registros correctamente, tanto en la **vista** como en el **localStorage**.
- Actualiza tu repositorio en GitHub.

</details>

---

## 📚 Archivos de Teoría y Práctica

- [¿Qué es el DataBinding? y los tipos de dataBinding en Angular](docs/1dataBinding.pdf)
- [Formularios en Angular: Template y Reactivos](docs/2formulariosAngular.pdf)
- [Práctica de Empleados. Clase#3. Formulario](docs/3Práctica_empleados_clase3_Formulario.pdf)

---

## 🚀 Instrucciones para Ejecutar el Proyecto

### 1. Instalación de dependencias

Ejecuta el siguiente comando en la raíz del proyecto para instalar las dependencias:

```bash
npm install
```

### 2. Servidor de desarrollo

Para iniciar el servidor de desarrollo y ver la aplicación en tu navegador:

```bash
ng serve
```

Luego abre [http://localhost:4200/](http://localhost:4200/) en tu navegador.

### 3. Generar un nuevo componente

Para crear un nuevo componente (por ejemplo, `agregar-empleado`):

```bash
ng generate component componentes/agregar-empleado
```

### 4. Ejecutar pruebas unitarias

Para correr los tests unitarios con Karma:

```bash
ng test
```

---

## 🛠️ Recursos adicionales

- [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli)
- [Documentación oficial de Angular](https://angular.dev/)

---

## ℹ️ Notas

- El archivo [`src/data/plantilla.json`](src/data/plantilla.json) contiene la plantilla de empleados utilizada por el servicio.
- El servicio principal para la gestión de empleados es [`EmpleadosService`](src/app/empleados.service.ts).
- El componente principal de listado es [`ListarEmpleadosComponent`](src/app/componentes/listar-empleados/listar-empleados.component.ts).

---

¡Recuerda mantener tu repositorio actualizado y seguir las buenas prácticas de desarrollo!
