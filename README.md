# SecureAI Support Site (Static Build)

Pre-built static HTML for the SecureAI support center. Deployed automatically from [`Tromml/secureai-support`](https://github.com/Tromml/secureai-support).

## Render Setup

| Setting | Value |
|---------|-------|
| **Environment** | Static Site |
| **Branch** | `main` |
| **Build Command** | _(leave empty -- already built)_ |
| **Publish Directory** | `.` |

No build step needed. Render serves the HTML files directly from this repo.

## Manual Deploy

From the source repo with Strapi running:

```sh
./scripts/deploy-site.sh
```
