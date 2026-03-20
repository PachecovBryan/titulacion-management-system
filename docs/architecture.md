# Arquitectura del sistema

## Tipo de arquitectura

El sistema sigue una arquitectura cliente-servidor basada en API REST, con separación clara entre frontend y backend.

---

## Componentes principales

### Frontend

- Aplicación SPA desarrollada en React
- Uso de Mantine para la interfaz de usuario
- Consumo de API REST para operaciones de negocio

---

### Backend

- API REST desarrollada en Node.js
- Manejo de lógica de negocio
- Validación de datos
- Exposición de endpoints para gestión de recursos

---

### Base de datos

- Sistema relacional PostgreSQL
- Modelado basado en entidades como:
  - Expedientes
  - Usuarios
  - Carreras
  - Comité académico
  - Evidencias

---

## Flujo general de comunicación

Cliente (React) → API REST (Node.js) → Base de datos (PostgreSQL)

---

## Infraestructura de despliegue

- Frontend: Vercel
- Backend: Render
- Base de datos: Supabase

---

## Consideraciones de diseño

- Separación de responsabilidades (frontend/backend)
- Escalabilidad horizontal del backend
- Persistencia estructurada con base de datos relacional
- Preparado para integración con otros sistemas académicos