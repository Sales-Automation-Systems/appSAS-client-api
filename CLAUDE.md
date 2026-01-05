@~/.claude/CLAUDE.md

# appSAS-client-api

API documentation for Sales Automation Systems clients - explains how to stream CRM events to SAS.

## Structure
```
index.html      # Documentation page (Swagger UI or similar)
openapi.yaml    # OpenAPI 3.x specification
favicon.svg     # Site favicon
vercel.json     # Vercel deployment config
```

## Deploy
- Platform: Vercel
- Branch: main → production
- Static site - no build step

## Editing
- Update `openapi.yaml` to modify API documentation
- The `index.html` renders the OpenAPI spec
- No npm/node required - pure static files

## Notes
- This is client-facing documentation
- Keep the OpenAPI spec accurate and up-to-date
- Test locally by opening index.html in browser
