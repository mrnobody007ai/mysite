# MySite — Personal Consultancy + Tech Blog

This repository is a starter scaffold for a personal site using Astro, Tailwind CSS, and MDX.

Local dev (PowerShell):

```powershell
cd "c:\Users\Tech Palli\Mysite"
npm install
npm run dev
```

Notes:
- Replace the Formspree action in `src/pages/contact.astro` with your form endpoint.
- To create a GitHub remote and push, you can use the GitHub CLI:

```powershell
gh repo create <your-username>/mysite --public --source=. --push
```

Deploy:
- Vercel: connect the repo and deploy (Astro is supported by default).
- Netlify: connect repo and set build command `npm run build` and publish directory `dist`.

Content guidelines:
- Blog posts live in `src/content/posts` as `.mdx` files with frontmatter: `title`, `date`, `description`.
