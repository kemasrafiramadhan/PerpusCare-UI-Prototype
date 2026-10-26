# PerpusCare UI Prototype

Static HTML/CSS/JavaScript prototype for Netlify. This is a presentation/demo UI only and does not connect to PHP or MySQL.

## Deploy on Netlify from GitHub
1. Upload the contents of this folder to a GitHub repository (the `index.html` must be in the repository root).
2. In Netlify, choose **Add new project** → **Import an existing project** → GitHub.
3. Select the repository.
4. Set **Build command** to blank / no build command and **Publish directory** to `.` (repository root).
5. Deploy. Future pushes to the connected branch will trigger deploys automatically.

The sample data and create/edit/delete interactions are only in browser memory. Refreshing the page resets to sample data. Do not put MySQL passwords or production credentials in this repository.
