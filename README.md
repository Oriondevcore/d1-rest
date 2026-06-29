# Cloudflare D1 REST API

Simple CRUD REST API built with Hono and Cloudflare D1. Example patterns for building SQLite-backed Workers.

## Endpoints

- GET /api/items — list all
- GET /api/items/:id — get one
- POST /api/items — create
- PUT /api/items/:id — update
- DELETE /api/items/:id — delete

## Deploy

```bash
npx wrangler deploy
```

## License

MIT
