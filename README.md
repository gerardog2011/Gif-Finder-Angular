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


| ![Vista Principal]<img width="1059" height="583" alt="image" src="https://github.com/user-attachments/assets/335174b7-c819-4ab6-958b-be0494f71825" />
 | ![Búsqueda]<img width="1070" height="576" alt="image" src="https://github.com/user-attachments/assets/b4ce78a9-134d-4f5e-9d16-4e1b3910b6cd" />
|

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
src/app/
├── gifs/
│   ├── components/
│   │   ├── gif-list/           # Lista de gifs
│   │   ├── gif-list-item/      # Item individual de gif
│   │   ├── side-menu/          # Menú lateral de navegación
│   │   └── side-menu-header/   # Cabecera del menú
│   ├── interfaces/             # Interfaces TypeScript
│   │   ├── gif.interface.ts
│   │   └── giphy.interface.ts
│   ├── pages/                  # Páginas principales
│   │   ├── dashboard-page/     # Página principal
│   │   ├── search-page/        # Página de búsqueda
│   │   ├── trending-page/      # Gifs populares
│   │   └── gif-history/        # Historial de búsquedas
│   ├── services/               # Servicios
│   │   └── gifs.service.ts     # Servicio para API de Gifs
│   └── mapper/                 # Mapeadores de datos
│       └── gif.mapper.ts       # Transformación de datos API
├── assets/                     # Recursos estáticos
└── environments/               # Configuraciones de entorno
