# 🧠 Prueba Técnica Full Stack - Wompi

Este repositorio contiene la solución a la prueba técnica Full Stack, utilizando **NestJS** para el backend y **React** para el frontend.

## 📁 Estructura del Proyecto

```
PruebaTecnicaFullStack/
├── backend-wompi/   # API REST construida con NestJS
└── frontend-wompi/  # Interfaz de usuario construida con React
```

---

## 🚀 Cómo ejecutar el proyecto localmente

### Requisitos previos

- Node.js 18+
- npm o yarn
- Git
- (Opcional) Docker

---

### 🔧 Backend (NestJS)

1. Ir al directorio del backend:
   ```bash
   cd backend-wompi
   ```

2. Instalar dependencias:
   ```bash
   npm install
   ```

3. (Opcional) Crear archivo `.env`:
   ```env
   PORT=3001
   ```

4. Ejecutar el servidor:
   ```bash
   npm run start
   ```

5. El backend estará corriendo en:
   ```
   http://localhost:3001
   ```

---

### 🎨 Frontend (React)

1. Ir al directorio del frontend:
   ```bash
   cd ../frontend-wompi
   ```

2. Instalar dependencias:
   ```bash
   npm install
   ```

3. Ejecutar la aplicación:
   ```bash
   npm run dev
   ```

4. El frontend estará disponible en:
   ```
   http://localhost:3000
   ```

5. Asegúrate de que el frontend esté apuntando al backend en `http://localhost:3001`.

---

## 📡 API - Endpoints principales (ejemplos)

| Método | Endpoint           | Descripción                    |
|--------|--------------------|--------------------------------|
| GET    | `/`                | Endpoint de prueba             |
| GET    | `/api/usuarios`    | Listar usuarios (ejemplo)      |
| POST   | `/api/pagos`       | Crear un pago (ejemplo)        |

---

## 🛠️ Tecnologías utilizadas

- **Backend**: NestJS, TypeScript
- **Frontend**: React, Vite (o CRA), Axios
- **Base de datos**: (Indicar si usás alguna: PostgreSQL, MongoDB, etc.)
- **Otros**: (opcional: Docker, Prisma, etc.)

---

## ✍️ Autor

William Alexis Peñaranda Castro  
[GitHub](https://github.com/ing-alexsipenaranda)

---
