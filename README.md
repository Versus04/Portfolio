# Android Developer Portfolio

Dark, minimalist multi-page portfolio for an Android developer. Built with vanilla HTML/CSS/JS so it can be hosted anywhere (GitHub Pages, Netlify, Vercel, etc.).

Pages
- Home (`/index.html`)
- Projects (`/projects/index.html`) + detail pages
- Blog (`/blog/index.html`) + posts
- About (`/about/index.html`)
- Contact (`/contact/index.html`) with Formspree-ready form

How to run locally (Windows PowerShell)
1. Open the folder in VS Code.
2. Use Live Server extension or any static file server.
   - With Python (optional): `python -m http.server 8080` then open http://localhost:8080

Customize
- Replace placeholder text, links, and email.
- Update social links in the header/footer.
- Swap the accent color in `assets/css/styles.css` if desired.
- Add your own images to `assets/images/` and replace placeholders.
- Replace `assets/resume.pdf` with your resume.

Blog
- Duplicate a post (e.g., `blog/post-1.html`) and update title/meta/content. Link it from `blog/index.html`.

Contact form
- Create a Formspree form and replace the `action` URL in `contact/index.html` with your endpoint.

SEO
- Update `<title>` and `<meta name="description">` per page.

License
MIT.
