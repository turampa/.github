# Cómo contribuir a Rampa

Gracias por ayudar a construir Rampa. Esta guía aplica a todos los repositorios de la organización.

## Antes de empezar

1. Busca si ya existe un issue sobre lo que quieres hacer.
2. Si no existe, abre uno con la plantilla que corresponda (error o nueva función).
3. Espera a que alguien del equipo lo etiquete como `listo` antes de escribir código grande.

## Ramas

- `main` siempre está estable y desplegable. Nadie hace push directo a `main`.
- Crea tu rama desde `main` con este formato:
  - `feat/descripcion-corta` para funciones nuevas
  - `fix/descripcion-corta` para correcciones
  - `docs/descripcion-corta` para documentación
  - `chore/descripcion-corta` para mantenimiento

## Commits

Usamos [Conventional Commits](https://www.conventionalcommits.org/es/v1.0.0/):

```
feat(baraja): agregar gesto de volver a la oferta anterior
fix(aplicar): validar mínimo de caracteres en las dos preguntas
docs(producto): documentar reglas del ranking
```

## Pull requests

1. Un PR resuelve un solo tema. Si crece mucho, divídelo.
2. Llena la plantilla del PR y enlaza el issue (`Cierra #123`).
3. Necesita **al menos una aprobación** y que pasen las verificaciones automáticas.
4. Usamos **squash and merge** para mantener el historial limpio.
5. Borra la rama después de fusionarla.

## Datos personales

Rampa maneja datos de estudiantes. Nunca subas datos reales de personas (nombres, cédulas, correos, CVs) a un repositorio, issue o PR. Usa datos de ejemplo.

## Idioma

Documentación, issues y PRs en español. Nombres de variables, funciones y archivos de código en inglés.
