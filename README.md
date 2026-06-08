# Henry Huang — Portfolio

Personal portfolio site built with [devportfolio](https://github.com/RyanFitzgerald/devportfolio) (Astro + Tailwind CSS).

## Local Development

```bash
npm install
npm run dev
```

Open [http://localhost:4321](http://localhost:4321) in your browser.

## Editing Content

Content is separated from code. Edit the JSON files in `src/data/`:

| File | What it controls |
|---|---|
| `src/config.ts` | Site settings (name, title, description, accent color, social links) |
| `src/data/about.json` | About me text |
| `src/data/skills.json` | Skills list |
| `src/data/projects.json` | Projects (name, description, link, image, skills) |
| `src/data/experience.json` | Work experience entries |
| `src/data/education.json` | Education entries |

To remove a section, empty the array (e.g. `[]`) or delete the file — the template will hide it automatically.

### Adding a Project Image

1. Place the image in `public/images/`
2. Add an `image` field to the project in `src/data/projects.json`:

```json
{
  "name": "Project Name",
  "description": "...",
  "link": "https://...",
  "image": "/images/your-image.jpg",
  "skills": ["..."]
}
```

## Remote Deployment (GitHub Pages)

The site deploys automatically via GitHub Actions on every push to `master`.

### Initial Setup

1. Go to the repo on GitHub → **Settings** → **Pages**
2. Under **Source**, select **GitHub Actions**
3. Push to `master` — the workflow at `.github/workflows/deploy.yml` will build and deploy

### Manual Deploy

If needed, trigger a deploy from the **Actions** tab → **Deploy to GitHub Pages** → **Run workflow**.

## Build

```bash
npm run build    # outputs to dist/
npm run preview  # preview the built site locally
```
