# 🧠 Simulador de Carrito con useReducer en React

📌 **Descripción (Español)**  
Este proyecto es una aplicación desarrollada con **React 19** que simula el funcionamiento de un carrito de compras. A nivel técnico, implementa un sistema de **estado global compartido** utilizando la **Context API nativa de React** en combinación con el hook **`useReducer`**, lo que permite gestionar de forma centralizada operaciones como agregar productos, actualizar cantidades o eliminar ítems del carrito.

La estructura basada en `useReducer` junto a `createContext` y `useContext` permite desacoplar completamente la lógica de negocio (reducer) de los componentes visuales, facilitando así la escalabilidad y mantenibilidad del proyecto. Esta arquitectura imita patrones similares a Redux pero con herramientas provistas 100% por React, sin dependencias externas.

---

📌 **Description (English)**  
This project is a **React 19** application that simulates a shopping cart system. It demonstrates the implementation of a **global shared state** architecture using React’s built-in **Context API** combined with the **`useReducer`** hook, allowing centralized control over cart actions such as adding items, updating quantities, and removing products.

The use of `useReducer` together with `createContext` and `useContext` enables a clean separation between state management logic and UI components. This architecture mimics Redux-style state containers but remains fully native to React, with zero external dependencies—ideal for scalable and maintainable codebases.

---

## 🚀 Tecnologías / Tech Stack

- React 19  
- Vite  
- JavaScript (ES6+)  
- CSS

---

## ⚙️ Funcionalidades / Features

- 🛒 Gestión completa de un carrito de compras
- 🔁 Estado global compartido con `createContext` + `useReducer`
- ⚖️ Cálculo dinámico del total según el contenido del carrito
- ♻️ Componentes desacoplados de la lógica de estado
- ✅ Validación de cantidad mínima para evitar estados inconsistentes

---

## 🔧 Instalación / Installation

```bash
clone
npm install
npm run dev
