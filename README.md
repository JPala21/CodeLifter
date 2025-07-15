# 🏋️‍♂️ CodeLifter

**CodeLifter** es una aplicación web desarrollada con **React**, **TypeScript** y **CSS puro**. Nace como un proyecto personal con el objetivo de construir un sistema completo de gimnasio, desde el seguimiento de rutinas hasta la gestión de entrenamientos y progresos físicos.

Diseñado desde cero por un dev que también entrena 💪👨‍💻

---

## 🚀 Objetivo

Crear una plataforma web para:
- Planificar y visualizar rutinas de entrenamiento
- Registrar ejercicios, repeticiones y tiempos
- Hacer seguimiento de avances personales
- Aprender y practicar tecnologías modernas de frontend (React + TS)
- Tener control completo de diseño (UI en Figma) y desarrollo

---

## ⚙️ Tecnologías utilizadas

- **React + Vite**
- **TypeScript**
- **CSS puro (sin frameworks de UI)**
- **Figma** (diseño previo)
- (Más adelante: Posible integración con un backend en Node o Supabase)

---

## 📁 Estructura del proyecto

```txt
src/
│
├── assets/             # Imágenes, íconos, fuentes, etc.
│
├── components/         # Componentes reutilizables (Botón, Card, Header, etc.)
│
├── pages/              # Cada pantalla o vista completa (Home.tsx, Rutinas.tsx, etc.)
│
├── layouts/            # Estructuras de página (por ejemplo, con header + footer)
│
├── hooks/              # Hooks personalizados (useAuth, useFetch, etc.)
│
├── services/           # Lógica para llamar APIs o manejar datos
│   └── api.ts
│
├── store/              # Estado global si usas Context o Redux (opcional)
│
├── utils/              # Funciones helpers, formateadores, validaciones
│
├── App.tsx             # Punto central de rutas y layouts
├── main.tsx            # Punto de entrada (ReactDOM.createRoot)
└── index.css           # Estilos base / globales

```
---
## 🛠️ Instalación y ejecución local

- yarn install

- yarn dev