Integrantes: Carlos Simbaña y Carlos Serrano

# Login Fullstack con Firebase y Supabase

Este ZIP contiene dos ejercicios completos para clase:

1. `firebase-login-fullstack`: React/Vite + Express + Firebase Auth + Firestore.
2. `supabase-login-fullstack`: React/Vite + Express + Supabase Auth + PostgreSQL.

Cada proyecto tiene:

- `frontend/`: formulario de email y clave, registro, login, logout y CRUD de productos protegido.
- `backend/`: API Express con validación de token y CRUD.
- `.env.example`: plantilla de variables de entorno.

## Requisitos

- Node.js 18 o superior.
- Proyecto creado en Firebase o Supabase.
- En Firebase: habilitar Authentication con Email/Password y crear Firestore.
- En Supabase: habilitar Auth Email/Password y ejecutar el SQL incluido en `supabase-login-fullstack/backend/schema.sql`.

## Ejecución rápida

Abre dos terminales por proyecto.

### Backend

```bash
cd backend
npm install
cp .env.example .env
npm run dev
```

### Frontend

```bash
cd frontend
npm install
cp .env.example .env
npm run dev
```

Luego abre:

```text
http://localhost:5173
```

## Importante

Los archivos `.env` reales no se incluyen por seguridad. Debes copiarlos desde `.env.example` y llenar tus credenciales.

Evidencia de funcionamiento
Evidencia de funcionamiento
<img width="1600" height="804" alt="image" src="https://github.com/user-attachments/assets/6174e655-e379-4767-93d5-cc9969cc64a4" />
<img width="1600" height="839" alt="image" src="https://github.com/user-attachments/assets/ea2bcdfc-0395-4ffe-8733-073f4ca2d3a3" />
