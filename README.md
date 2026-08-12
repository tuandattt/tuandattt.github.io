# tuandattt.github.io

Personal academic homepage — plain static HTML/CSS, no build step.

## Structure

```
index.html            all page content
assets/css/style.css  styling
assets/img/avatar.svg profile photo placeholder
assets/cv.pdf         CV (add your own)
```

## Editing

- Text, links, News and Publications entries: `index.html`
- Colors, fonts, spacing: the `:root` variables at the top of `assets/css/style.css`
- Profile photo: put your image in `assets/img/` and update the `<img class="avatar">` `src`
- CV: drop `cv.pdf` into `assets/`

## Preview locally

```bash
python -m http.server 8000
# open http://localhost:8000
```

## Deploy

Push to `main`; GitHub Pages serves it at https://tuandattt.github.io
(Settings → Pages → Source: `main` / root).
