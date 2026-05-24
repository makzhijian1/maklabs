# directusx

directusx is a playground for Directus-related code, including extensions and API explorations.

## directus-promoter

Runs two separate Directus instances with separate Postgres databases:

- Source: http://localhost:8055
- Target: http://localhost:8056

Default login for both:

- Email: `admin@example.com`
- Password: `password`

## Commands

```bash
make up
make down
```

`make down` keeps Docker volumes, so Directus data persists across restarts.
