# 3A-VLA project website

Official project website: https://3a-vla.github.io/

- Paper: https://arxiv.org/abs/2602.02212
- Code: https://github.com/zhouzheyuan/3a-vla
- Model: https://huggingface.co/3a-vla/3A-VLA-Qwen3.5-4B-GameForPeace
- Dataset: https://huggingface.co/datasets/3a-vla/AceAction-GameForPeace

## Editing and preview

This is a static website. Edit `index.html`, CSS, JavaScript and the files in `assets/` directly. Video assets retain their original delivery quality and stream through the bundled HLS player.

Run `python3 -m http.server 8039` from this directory to preview the site.

## GitHub Pages

Publish from the `main` branch and the repository root (`/`). `.nojekyll` keeps the site and media files as plain static assets. No build step is required.
