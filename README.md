# Shiela Mae Putungan — Portfolio

A responsive personal portfolio built with React + Vite for GitHub and remote job applications.

## Focus

- Virtual assistance
- Data entry and data analysis
- Microsoft Excel
- Construction support
- AutoCAD and SketchUp
- Administrative support
- Digital content

## Tech

- React
- Vite
- CSS
- Lucide React icons

## Run locally

```bash
npm install
npm run dev
```

Then open the local URL shown by Vite.

## Build

```bash
npm run build
npm run preview
```

## Customize

Open `src/main.jsx` and update the `LINKS` object:

```js
const LINKS = {
  github: "YOUR_GITHUB_URL",
  linkedin: "YOUR_LINKEDIN_URL",
  onlinejobs: "YOUR_ONLINEJOBS_URL",
  email: "YOUR_EMAIL"
};
```

Replace the project descriptions and project links when real repositories or portfolio files are available.

### Resume

Place your real resume at:

`public/resume.pdf`

The current download buttons already point to `/resume.pdf`.

### Project images

Add images inside:

`public/images/`

Then replace the project visual placeholders with image elements when your screenshots are ready.

## Contact form

The current contact form is intentionally a front-end demo and does not pretend to send messages.

To make it functional, connect it to a service such as Formspree or EmailJS and replace the `onSubmit` handler in `src/main.jsx`.

## Deployment

### Vercel

1. Push the repository to GitHub.
2. Import the repository into Vercel.
3. Vercel should detect Vite automatically.
4. Deploy.

### Netlify

1. Push the repository to GitHub.
2. Create a new Netlify site from the repository.
3. Build command: `npm run build`
4. Publish directory: `dist`

### GitHub

Create the repository, then:

```bash
git init
git add .
git commit -m "Create personal portfolio"
git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main
```

## Content accuracy

The portfolio intentionally avoids inventing employers, clients, professional statistics, or years of experience. Academic/sample projects should remain labeled as such unless they become real client work.
