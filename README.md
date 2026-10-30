# 4ntaury.github.io

Cybersecurity, Reverse Engineering & Systems Forensics blog built with [Hugo](https://gohugo.io/) and [PaperMod](https://github.com/adityatelange/hugo-PaperMod).

Live site: **https://4ntaury.github.io/**

## Local Development

Preview locally with live reload:

```bash
hugo server -D
```

Then open `http://localhost:1313`.

## Publishing a New Post

1. Create a new Markdown article under `content/posts/`:
   ```bash
   hugo new content posts/your-post-slug.md
   ```
2. Edit the frontmatter (`draft: false` when ready to publish) and write your Markdown content.
3. Commit and push to `main`:
   ```bash
   git add .
   git commit -m "Add post: Your Post Title"
   git push
   ```
   GitHub Actions automatically builds and deploys the site to GitHub Pages within ~30 seconds.
