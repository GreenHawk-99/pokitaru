# Pokitaru

Pokitaru is a React and TypeScript web app for managing and supervising game servers, with a downloader and
notifications.

## Related projects

- [Veldin](file:///C:/Users/green/PycharmProjects/veldin) — downloader backend.
- [Kalebo](file:///C:/Users/green/IdeaProjects/kalebo) — main API and database gateway.
- See [`guideline.md`](guideline.md) for endpoint mappings and the frontend/backend request flow.

## Development

- `npm install` — install dependencies
- `npm run dev` — start the local Vite server
- `npm run build` — type-check and build
- `npm test` — run tests
- `npm run lint` — lint the code

Runtime endpoints and environment settings are in `public/config/config.local.yaml` and
`public/config/config.prod.yaml`.
