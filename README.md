# ZKAS.io View Counter

Cloudflare Worker backing the page-view counter on https://zkas.io.

- GET /api/views returns the current count.
- POST /api/views increments the count and returns the new value.
- Uses the Cloudflare KV binding SITE_VIEWS.
