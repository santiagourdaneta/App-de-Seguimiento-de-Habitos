
Una aplicación fullstack moderna para gestionar y hacer seguimiento de hábitos personales, construida con tecnologías de última generación.

## 🧩 Tecnologías

### 🔹 Frontend (Next.js)
- **React + Next.js** (App Router)
- **Tailwind CSS** para estilos rápidos y responsivos
- **ShadCN/UI** para componentes reutilizables y accesibles
- **Clerk** para autenticación segura y gestión de usuarios

### 🔹 Backend (NestJS)
- **NestJS** como servidor API modular y escalable
- **Prisma ORM** para interactuar con **PostgreSQL**
- **JWT + AuthGuard** para proteger las rutas privadas

---

## 🚀 Funcionalidades

- ✅ Registro/Login de usuarios (Clerk)
- ✅ Crear, editar y eliminar hábitos
- ✅ Marcar hábitos como completados por día
- ✅ Dashboard con progreso semanal
- ✅ Backend seguro con JWT y roles
- ✅ UI limpia y responsiva (ShadCN)

---

## 📦 Instalación Local

### 1. Clona el repositorio

git clone https://github.com/santiagourdaneta/App-de-Seguimiento-de-Habitos/
cd habit-tracker-app

## 2. Configura el frontend

cd frontend
npm install
# Crea archivo .env.local basado en .env.example
npm run dev

## 3. Configura el backend

cd ../backend
npm install
# Crea archivo .env con tus variables de entorno
npx prisma migrate dev
npm run start:dev
