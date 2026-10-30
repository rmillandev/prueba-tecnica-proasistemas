# Arranque de la prueba técnica de backend

Proyecto NestJS listo para correr. Es el punto de partida de la prueba, para que no gastes tiempo en instalar y configurar.

Trae **solo lo que genera el CLI de Nest**. No hay estructura de capas, ni entidades, ni interfaces de repositorio, ni librerías escogidas por nosotros. Cómo organizas el código es tu decisión y es parte de lo que se evalúa, así que cuéntanos en voz alta por qué lo organizas así.

## Requisitos

- **Node 22** (está en `.nvmrc`, con `nvm use` queda listo).
- **npm 10 o superior.** Con npm 9.2 la instalación falla. Revisa con `npm -v` antes de empezar.

## Cómo correrlo

```bash
npm install
npm run start:dev    # queda en http://localhost:3000
```

Para comprobar que todo está bien antes de arrancar:

```bash
curl http://localhost:3000    # responde: Hello World!
npm test                      # pasa 1 prueba
```

## Scripts

| Script | Qué hace |
|--------|----------|
| `npm run start:dev` | Levanta la API en modo watch |
| `npm run build` | Compila a `dist/` |
| `npm test` | Corre las pruebas con Vitest |
| `npm run test:watch` | Pruebas en modo watch |
| `npm run lint` | Revisa el código con oxlint |
| `npm run format` | Formatea con Prettier |

## Antes de entregar

Reemplaza este archivo por tu propio `README.md`, con cómo se corre tu proyecto, qué decisiones tomaste, qué dejaste afuera y qué harías con más tiempo.
