# src/components/layout

Este directorio contiene componentes de estructura visual global (layout) de la aplicacion.

Ejemplos para este CRM:

- Sidebar principal de navegacion.
- Header con contexto de empresa/equipo.
- Layout base de dashboard.

Recomendacion:

- Usa subdirectorios por componente.
- Mantiene consistencia con el formato componente + story + test + index.

Ejemplo:

- layout/Sidebar/
  - SidebarItem/
    - SidebarItem.tsx
    - SidebarItem.stories.tsx
    - SidebarItem.test.tsx
  - SidebarSection/
    - SidebarSection.tsx
    - SidebarSection.stories.tsx
    - SidebarSection.test.tsx
  - Sidebar/
    - Sidebar.tsx
    - Sidebar.stories.tsx
    - Sidebar.test.tsx
  - index.ts
