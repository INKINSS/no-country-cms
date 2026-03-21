# src/components/forms

Este directorio contiene componentes de formularios reutilizables.

Para este CRM, aqui pueden vivir controles compartidos como:

- Inputs de contacto (email, telefono, nombre, empresa).
- Selectores de etapa del pipeline.
- Campos de filtros para reportes.

Cada componente debe estar en su propia carpeta con index.ts para exportaciones.

Ejemplo:

- forms/Input
  - Input.tsx
  - Input.stories.tsx
  - Input.test.tsx
  - index.ts
