# 📱 Prácticas y Proyectos en Flutter

Repositorio dedicado al desarrollo de aplicaciones móviles multiplataforma construidas con **Flutter** y **Dart**, enfocado en buenas prácticas de arquitectura, manejo de estado reactivo y consumo de servicios web.

---

## 📂 Contenido del Repositorio

| Proyecto | Descripción | Tecnologías / Conceptos Clave |
| :--- | :--- | :--- |
| **[Calculadora Móvil](./calculadora_p_1)** | Aplicación interactiva de operaciones matemáticas con diseño responsivo. | Flutter, Dart, `setState`, UI Dinámica |
| **[Módulo de Login & API](./prueba_login)** | Sistema de autenticación de usuarios consumiendo una API RESTful. | HTTP, Asincronía (`async`/`await`), JSON Decoding, Validación de formularios |

---

## 🛠️ Detalle de los Proyectos

### 1. 🧮 Calculadora Móvil (`calculadora_p_1`)
Aplicación orientada al diseño de interfaces limpias y el manejo de lógica aritmética reactiva en Flutter.

* **Características principales:**
  * Interfaz de usuario intuitiva y adaptada a diferentes resoluciones de pantalla.
  * Separación de la lógica matemática de la capa de presentación.
  * Gestión del estado de la pantalla mediante widgets con estado (`StatelessWidget`).

---

### 2. 🔐 Módulo de Autenticación con API REST (`prueba_login`)
Implementación de un flujo de inicio de sesión con integración a backend mediante servicios web.

* **Características principales:**
  * Formulario con validación de entradas (correo, contraseña y campos requeridos).
  * Consumo de endpoints de autenticación mediante peticiones HTTP (método POST).
  * Control de estados de la interfaz: carga (*loading spinner*), error de credenciales y éxito.
  * Decodificación y manipulación de respuestas en formato JSON.

---

## 🚀 Requisitos y Ejecución Local

Para ejecutar cualquiera de las aplicaciones en un emulador o dispositivo físico:

1. Clonar el repositorio:
   ```bash
   git clone [https://github.com/UrielEspinoza7/practicas-flutter.git](https://github.com/UrielEspinoza7/practicas-flutter.git)
