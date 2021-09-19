# Hugo Link in Bio

[![Netlify Status](https://api.netlify.com/api/v1/badges/8224c8e4-ea2b-4544-8251-541b27895c25/deploy-status)](https://app.netlify.com/sites/hugo-link-bio/deploys)

Link in bio page powered by Hugo. Live demo: https://hugo-link-bio.netlify.app/

# Create new link

```bash
hugo new link/link-name.md
```

Fill the `thumbnail` and `link` front-matter.

Example:

```yaml
---
thumbnail: /img/thumbnail/github.png
link: http://github.com/ardianta
---
```