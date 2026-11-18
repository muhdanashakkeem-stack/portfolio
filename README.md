# Muhammed Anas Hakkeem — Portfolio

A responsive, single-page personal portfolio built with HTML, CSS, and JavaScript in one `index.html` file.

## Project structure

```text
portfolio/
├── index.html
├── README.md
└── public/
    ├── resume.pdf
    └── assets/
        └── profile-photo.jpg
```

## Add your profile photo

Place your photo at:

`public/assets/profile-photo.jpg`

If the file is not present, the page displays a temporary MAH placeholder.

## Update contact details

Open `index.html` and edit the `CONTACT` object near the bottom of the file. Note that values embedded in public website source code can be inspected by visitors.

## Resume

Place your PDF at `public/resume.pdf`. If your original file is in a ZIP archive, extract it first and copy the PDF into this location.

## Run locally

Open `index.html` in a browser. For a local static server, you can use the VS Code Live Server extension.

## Publish with GitHub Pages

1. Create a GitHub repository named `portfolio` (or another name).
2. Upload the contents of this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then save.
6. Wait for GitHub Pages to publish the site.

## Git commands

```bash
git init
git add .
git commit -m "Initial portfolio website"
git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your actual repository URL. Never commit passwords, access tokens, or private credentials.
