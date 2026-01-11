# App Legal Documents

Auto-generated Privacy Policies and Terms of Service for iOS apps.

**Live at:** https://docs.nikitin.fyi

## Structure

```
/
├── index.html              # Main page listing all apps
├── style.css               # Shared styles
├── {bundle-id}/            # Per-app documents
│   ├── privacy-policy.html
│   └── terms-of-service.html
```

## URLs

Each app gets:
- `https://docs.nikitin.fyi/{bundle-id}/privacy-policy.html`
- `https://docs.nikitin.fyi/{bundle-id}/terms-of-service.html`

## Auto-deployment

This repo is connected to Coolify. Any push to `main` triggers automatic deployment.

---

Generated and managed by the `legal-docs-generator` Claude Code skill.
