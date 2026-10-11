# Zaoqu Liu

Personal academic website at **[zaoqu-liu.github.io](https://zaoqu-liu.github.io/)**

A bilingual site covering research, publications, education, and honors

## Run locally

```sh
python3 -m http.server 4320 --bind 127.0.0.1
```

Open `http://127.0.0.1:4320/`. No build step or runtime dependencies are required

## Maintain

- Edit `index.html` for content, styles, and behavior
- English and dark mode are the defaults; `?lang=zh&theme=light` selects Chinese and light mode
- Publications and honors each display six entries initially; their existing controls expand and collapse the full lists
- Add entries to the corresponding list; totals are calculated automatically
- Store images in `assets/`; retain the notices in `THIRD_PARTY_NOTICES.md`
- Citation metrics are a dated snapshot, not a live feed

GitHub Pages publishes the repository root from `master`. Submit changes through a pull request; merging updates the public website

Personal content and photographs are not licensed for reuse. Third-party assets retain their respective terms
