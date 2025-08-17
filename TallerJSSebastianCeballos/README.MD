# PokéDex Alola — Taller Avanzado

## 📌 Descripción
Este proyecto es una versión avanzada de la Pokédex basada en **Pokémon Sol y Luna (Región de Alola)**. Implementa una estructura de página profesional con **sistema de filtros interactivos**, diseño responsive y mejoras en la experiencia de usuario.

La aplicación consume datos de la **[PokeAPI](https://pokeapi.co/)** para mostrar información de los Pokémon hasta la **séptima generación (Alola)**.

---

## 🎯 Funcionalidades Principales

### Estructura de Página
- **Header**: Navegación principal, búsqueda global y toggle de modo oscuro.
- **Sidebar**: Panel de filtros por tipo, generación, ordenamiento, acciones y estadísticas.
- **Main Content**: Grid de tarjetas de Pokémon con paginación.
- **Footer**: Créditos e información adicional.

### Sistema de Filtros
- 🔎 **Búsqueda por nombre** (en tiempo real con *debouncing*).
- 🧪 **Filtro por tipo** (selección múltiple).
- 🌍 **Filtro por generación** (Kanto → Alola).
- 📊 **Ordenamiento**: por ID, nombre, altura o peso.
- 🧹 **Limpiar filtros** con un solo clic.

### Experiencia de Usuario
- 📱 **Responsive design** (desktop y mobile).
- ⏳ **Loading states** con *skeletons*.
- 🚫 **Estados vacíos** cuando no hay resultados.
- ✨ **Animaciones suaves** y efectos hover.
- ⭐ **Favoritos** persistentes en `localStorage`.
- 📑 **Paginación** con navegación entre páginas.
- 📤 **Exportar JSON** de la lista filtrada.
- 🌙 **Modo oscuro** configurable.
- 🔍 **Modal de detalles** con stats y habilidades.

---

## 🛠️ Tecnologías Utilizadas
- **HTML5 semántico**
- **CSS3 con TailwindCSS** (layouts responsivos y estilos rápidos)
- **JavaScript ES6+**
  - Gestión de estado con objetos
  - Filtrado y ordenamiento dinámico
  - Event delegation para eficiencia
  - Debouncing en la búsqueda
  - Cache y lazy loading para optimizar peticiones
- **PokeAPI REST** para consumo de datos

---

## 📂 Estructura de Archivos
📦 pokeDex-alola
┣ 📜 index.html # Estructura semántica de la aplicación
┣ 📜 script.js # Lógica de filtros, render y eventos
┣ 📜 styles.css # (Opcional) Estilos adicionales
┣ 📜 README.md # Documentación del proyecto

---

## 🚀 Instalación y Uso
1. Clonar este repositorio o descargar los archivos.
2. Abrir `index.html` en un navegador moderno.
3. La aplicación cargará automáticamente los datos de la **PokeAPI**.

---

## 🧪 Funcionalidades Específicas
- **Búsqueda en tiempo real** con `setTimeout` y cancelación previa (*debounce*).
- **Filtros dinámicos por tipo** generados en JavaScript.
- **Ordenamiento** configurable (ID, nombre, altura, peso).
- **Modal de detalles** con stats y habilidades.
- **Sistema de favoritos** persistente en `localStorage`.
- **Exportar JSON** con la lista filtrada.

---

## 📜 Créditos
- Datos: [PokeAPI](https://pokeapi.co/)
- Diseño: Inspirado en proyectos comunitarios de Pokédex.
- Autor: Taller avanzado — Proyecto académico de práctica.
