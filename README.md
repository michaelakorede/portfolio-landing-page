# Michael Fakorede Portfolio Landing Page

Static, responsive portfolio landing page for IT, cloud infrastructure, systems administration, infrastructure support, IT specialist, and technical support roles.

## File Structure

```text
.
├── index.html
├── README.md
├── css/
│   └── styles.css
├── js/
│   └── script.js
└── assets/
    ├── docs/
    │   ├── Michael_Fakorede_Azure_DevOps_Engineer_Resume.pdf
    │   ├── Michael_Fakorede_Azure_DevOps_Engineer_Resume.docx
    │   ├── Michael_Fakorede_CV.pdf
    │   ├── Michael_Fakorede_Systems_Administrator.docx
    │   ├── Michael_Fakorede_Infrastructure_Support_Engineer.docx
    │   ├── Michael_Fakorede_IT_Specialist.docx
    │   └── Michael_Fakorede_Technical_Support_Engineer.docx
    └── images/
        ├── cloud-infrastructure-hero.png
        └── cloud-infrastructure-hero.webp
```

## How To Run Locally

Because this is a static site, you can open `index.html` directly in a browser.

Optional local server:

```powershell
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## How To Edit

- Update page content in `index.html`.
- Update colors, spacing, responsive layout, and animations in `css/styles.css`.
- Update mobile navigation or scroll animations in `js/script.js`.
- Replace resume downloads in `assets/docs/`.
- Replace the hero image in `assets/images/cloud-infrastructure-hero.webp`.

Notes:

- The page uses only local assets and no external framework.
- The hero image is generated and stored locally.
- The main portfolio content is based on `Michael_Fakorede_CV.pdf`.
- Native Google Docs version of the Azure DevOps Engineer resume: https://docs.google.com/document/d/16Q-qIS-EmstgHkn1lnk7zh432VY0MD4i3GFALJ1-63k

## Deploy To GitHub Pages

1. Create a GitHub repository.
2. Upload all files and folders from this directory.
3. In GitHub, go to `Settings` > `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select the `main` branch and `/root`.
6. Save. GitHub will publish the site and show the live URL.

## Deploy To Netlify

1. Sign in to Netlify.
2. Choose `Add new site` > `Deploy manually`.
3. Drag this project folder into Netlify.
4. Netlify will publish the static site automatically.

For Git-based deployment:

1. Push this folder to GitHub.
2. In Netlify, choose `Import from Git`.
3. Select the repository.
4. Leave build command blank.
5. Set publish directory to `.`.

## Deploy To Vercel

1. Sign in to Vercel.
2. Choose `Add New` > `Project`.
3. Import the GitHub repository.
4. Leave framework preset as `Other`.
5. Leave build command blank.
6. Set output directory to `.` if prompted.
7. Deploy.
