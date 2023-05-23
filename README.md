## Boilerplate for a REST-API on Express and TypeScript

This is mostly intended for my personal use -- Suggestions are welcome.

### Information

- Responses are enforced to follow the [JSend specification](https://github.com/omniti-labs/jsend).
- Uses [Zod](https://github.com/colinhacks/zod) for validation.
- CORS is enabled by default.
- Models should be placed in `src/models`, unless Prisma is used (`src/prisma`).

The error-handling is based on various sources (express' guide, etc.).
