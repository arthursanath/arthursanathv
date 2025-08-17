# Portfolio Starter (GitHub Pages + 3D CAD Viewer)

This starter is ready for **GitHub Pages** and includes an **interactive 3D viewer** using `<model-viewer>`.

## How to use (Step-by-step)
1. Create a GitHub repo named `yourusername.github.io` (public).
2. Download this folder as ZIP and extract.
3. Upload all files/folders to the repo (drag & drop on GitHub or use Git).
4. In the repo: Settings → Pages → Source: `Deploy from a branch` → Branch: `main` → Folder: `/root` → Save.
5. Your site will be live at `https://yourusername.github.io`.

## Add your CAD model
1. Export your CAD to **.glb** (recommended) or .gltf.
2. Put it into `/models/` (e.g., `/models/chassis.glb`).
3. Edit `index.html` → find `<model-viewer src="models/example.glb" ...>` and change the `src` path to your file.

> Tip: Keep files reasonably small (e.g., < 25–50 MB) for faster loading.

## Replace content
- `images/*` → replace placeholders with your renders/screenshots.
- `resume/Anubhav_Acharya_Resume.pdf` → add your real PDF and keep the same name (or update the link in the navbar).
- Text: Open `index.html` and edit headings, descriptions, and links.

## Multiple projects
Duplicate a project `<article class="card"> ... </article>` block in the `#projects` section for each project,
and add separate 3D models if needed by duplicating the `<model-viewer>` element with different `src` files.

## Local preview
You can open `index.html` directly in a browser. Some features may be limited locally; everything works once deployed on GitHub Pages.
