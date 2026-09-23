# enrico-02.github.io

Personal site of Enrico D'Amico — XR Project Manager and Unity developer, Milan.

Static site served by GitHub Pages. No build step: edit and push.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole site — one scrolling page |
| `styles.css` | All styling |
| `Images/` | Profile picture and project screenshots |
| `CV_Enrico_DAmico_EN.pdf` | CV linked from the nav |
| `CV_Enrico_DAmico_IT.pdf` | Italian CV |

## Adding a project screenshot

Each project card contains a placeholder:

```html
<div class="project-media">
  <!-- SCREENSHOT: Italy Decoded -->
  <div class="ph">Screenshot<br>Italy Decoded</div>
</div>
```

Replace the `<div class="ph">…</div>` with:

```html
<img src="Images/italy-decoded.jpg" alt="Italy Decoded — VR experience">
```

Keep screenshots at roughly 16:10, 1600px wide, under 300 KB each.

## Confidentiality

The virtual museum project is under NDA: no client name, no images, no links.
Do not change this without written confirmation from the studio.
