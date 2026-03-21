# src/components

Este directorio contiene componentes reutilizables en toda la aplicacion.

Regla general:

- Si un componente se reutiliza entre varias features, debe vivir aqui.
- Cada componente idealmente va en su propia carpeta con story, test e index de exportacion.

Ejemplo:

- src/components/ui/Example/
  - Example.tsx
  - Example.stories.tsx
  - Example.test.tsx
  - index.ts

Si un componente pertenece solo a una feature, ubicalo dentro de src/features/<feature>/components.
