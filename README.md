Saaketh Chenna | Portfolio

Welcome to the source code for my personal portfolio website.

The site is a single-page, static website built with HTML, CSS, and JavaScript. There is no build process or framework required, so it is simple to run, edit, and deploy.

🚀 Run Locally

You can open index.html directly in your browser, or run the site with a local server:

python3 -m http.server 8000

Then open http://localhost:8000 in your browser.

📁 Project Structure
index.html   Main website file containing the markup, styles, and scripts
assets/      Photos, logos, film posters, resume, and IEEE paper pages
✏️ Making Changes

Most updates can be made directly in index.html or the assets/ folder.

Colors

The main color palette is defined in the :root section at the top of the <style> tag. You can update variables such as:

--background, --foreground, --muted, --accent, --border, --card, and --k1 through --k5.

Content

All portfolio content can be edited directly in index.html, including:

Hero
Stats
About
Experience
Leadership
Projects
Documents
Skills
Off the Clock
Contact
Images

To update images or logos, replace the files in assets/ while keeping the existing filenames.

Resume & Paper Viewers

The resume and IEEE paper sections display individual page images. To update them, export the new PDF pages as JPEGs and replace the corresponding files in assets/.

🌐 Deploy with GitHub Pages

You can host the portfolio for free using GitHub Pages.

Open the repository on GitHub.
Go to Settings → Pages.
Under Build and deployment, select Deploy from a branch.
Select the main branch and / (root).
Save your changes.

Once deployed, your site will be available at: https://<your-username>.github.io/<repo-name>/
