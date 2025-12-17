# 🎬 GifsApp - Buscador de Gifs con Angular

[![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)](https://angular.io/)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

Una aplicación moderna y responsive para buscar y explorar gifs, desarrollada con Angular y TypeScript.

## ✨ Características Principales

- **🔍 Búsqueda en Tiempo Real**: Busca gifs por nombre, descripción o tags.
- **📱 Diseño Responsive**: Interfaz adaptable a todos los dispositivos.
- **🎯 Navegación Intuitiva**: Menú lateral con secciones de Trending y Búsqueda.
- **⚡ Componentes Modulares**: Arquitectura basada en componentes reutilizables.
- **🎨 UI Moderna**: Diseño limpio y atractivo con Tailwind CSS.

## 🖼️ Capturas de Pantalla

A continuación se muestran algunas capturas representativas del proyecto, donde se aprecia el diseño general, la estructura de la página y los principales componentes de la interfaz.

### Vista general del proyecto

| Página principal | Sección Menú |
|------------------|--------------|
| <img src="https://github.com/user-attachments/assets/de39ce3d-4291-4a89-9aae-ce58e7ea83e0" width="480"/> | <img src="https://github.com/user-attachments/assets/8f6b2667-efc8-4312-b82f-e8f86d0b8a75" width="480"/> |

---

### Secciones internas

| Sección Equipo | Sección Testimonios |
|---------------|---------------------|
| <img src="https://github.com/user-attachments/assets/8ed013e0-3205-43d1-b6cd-cb2b45bc0049" width="480"/> | <img src="https://github.com/user-attachments/assets/4fb3c96d-eb20-4400-9e0e-5f9437d1e4b4" width="480"/> |


## 🛠️ Tecnologías Utilizadas

### Frontend
- **Framework**: Angular 20+
- **Lenguaje**: TypeScript
- **Styling**: Tailwind CSS
- **Iconos**: Font Awesome
- **Estado**: Servicios Angular y RxJS

### APIs y Servicios
- **API de Gifs**: Giphy API

## 📦 Estructura del Proyecto
src/
app/
├── gifs/

│ ├── components/

│ │ ├── gif-list/ # Lista de gifs

│ │ ├── gif-list-item/ # Item individual de gif

│ │ ├── side-menu/ # Menú lateral de navegación

│ │ └── side-menu-header/ # Cabecera del menú


│ ├── interfaces/ # Interfaces TypeScript

│ │ ├── gif.interface.ts

│ │ └── giphy.interface.ts


│ ├── pages/ # Páginas principales

│ │ ├── dashboard-page/ # Página principal

│ │ ├── search-page/ # Página de búsqueda

│ │ ├── trending-page/ # Gifs populares

│ │ └── gif-history/ # Historial de búsquedas


│ ├── services/ # Servicios

│ │ └── gifs.service.ts # Servicio para API de Gifs


│ └── mapper/ # Mapeadores de datos


│ └── gif.mapper.ts # Transformación de datos API

## 🚀 Demo en vivo:
[Ver proyecto en Vercel](https://gifsearcherconangular.vercel.app)

## 📄 Licencia
MIT License - See [LICENSE.txt](LICENSE.txt) for details.

## 👨‍💻 Autor
Jafet Gerardo Guardia Soto

GitHub: @gerardog2011

LinkedIn: Gerardo Guardia

## 📚 Créditos
- Basado en el tutorial/proyecto de [Klerith/fernando-herrera] (curso de Angular)
- Gif API proporcionada por [Giphy]

