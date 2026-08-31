# smit@dublin:~

Interactive terminal portfolio of Smit Mehta — Senior Data Analyst & AI Engineer, Dublin.

A single-page, zero-build static site styled as an amber-phosphor CRT terminal:
boot sequence, working shell (type `help`), particle hologram portrait,
live GitHub and Dublin weather data, and a few easter eggs worth finding.

## Structure

```
index.html            the entire site: markup, styles, and scripts
assets/portrait.png   source image sampled by the hologram
```

Three.js r147 is lazy-loaded from CDN only when the hologram can run
(WebGL available, motion allowed). Everything degrades: no JS, no WebGL,
reduced motion, and readable mode all fall back to an ASCII portrait
and a plain page.

## Run locally

Any static server works:

```bash
npx http-server -p 4173 -c-1 .
```

Then open http://localhost:4173

## Contact

smitm515@gmail.com · [github.com/smitmehta19](https://github.com/smitmehta19) · [linkedin.com/in/smitmehta19](https://www.linkedin.com/in/smitmehta19)
