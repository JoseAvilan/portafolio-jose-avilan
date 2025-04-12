# 📒 CHANGELOG

Todas las modificaciones importantes de este proyecto serán documentadas aquí.

Este archivo sigue el formato [Keep a Changelog](https://keepachangelog.com/es/1.0.0/) y está versionado mediante [SemVer](https://semver.org/lang/es/).

---

## [0.2.1] - 2025-04-12

### Refactorizado
- Eliminado archivo `index.js` en `src/icons` por recomendación de mejores prácticas
- Reemplazadas importaciones agrupadas por importaciones directas de íconos

## [0.2.0] - 2025-04-11

### Agregado
- Componente `Navbar.astro` (antes `Header.astro`) con navegación flotante tipo dock (estilo macOS)
- Tooltips accesibles y navegación semántica (`role="navigation"`, `aria-label`)
- Estructura modular de íconos reutilizables en `src/icons`
- Implementación de archivo `index.js` para importación centralizada de íconos
- Preparación de sistema de traducciones (`i18n/es.js`) con textos base para navegación

### Refactorizado
- Renombrado `Header.astro` a `Navbar.astro` por claridad semántica y propósito real del componente
- Limpieza de imports en `Navbar` y adopción de clases dinámicas con `Astro.props` en íconos

---

## [0.1.0] - 2025-04-10

### Agregado
- Configuración inicial de Tailwind CSS v4 en Astro v5.6
- Fondo base en modo oscuro (`bg-zinc-900`)
- Archivos `Layout.astro`, `index.astro` y `global.css` organizados
- Archivo `tailwind.config.js` creado
- `.gitattributes` agregado para normalizar saltos de línea (LF)

---

## [Unreleased]

> Próximos pasos:
- Implementación de anclas internas y secciones reales (Inicio, Sobre mí, Proyectos, Contacto)
- Animaciones de entrada y scroll
- Toggle de modo oscuro / claro
- Selector de idioma (`es/en`)
