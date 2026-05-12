# Sajjad Daroudi Portfolio

Static GitHub Pages portfolio website for Sajjad Daroudi. The content is based on the public GitHub profile, Google Scholar/publication records, and the provided accomplishments/CV PDF.

## Files

- `index.html` contains all page sections and content.
- `styles.css` controls layout, typography, responsive behavior, and visual design.
- `script.js` handles the mobile menu and active navigation state.
- `assets/` stores the profile photo, CV PDF, and project images.

## Editing the Website

Edit `index.html` to update biography text, education, research highlights, projects, publications, skills, experience, contact links, and CV links.

Use placeholders where exact details are not yet known. Publications, awards, and achievements should only be added when verified.

## Updating Contact Links

Contact links are in the `#contact` section of `index.html`. Update the email, GitHub, Google Scholar, or LinkedIn URLs there when needed.

## Replacing the Profile Image

1. Add a professional headshot to the `assets/` folder.
2. Recommended filename: `profile.jpg` or `profile.png`.
3. In `index.html`, replace:

```html
assets/profile-placeholder.svg
```

with the new image path, for example:

```html
assets/profile.jpg
```

## Adding or Updating the CV

1. Export the CV or accomplishments document as a PDF.
2. Place it in the `assets/` folder.
3. Recommended filename:

```text
Sajjad_Daroudi_CV.pdf
```

4. The current CV buttons point to:

```text
assets/Sajjad_Daroudi_CV.pdf
```

## Replacing Project Images

Add project images to `assets/`, then update each project card image in `index.html`.

Example:

```html
<img src="assets/es-ekf-pose-estimation.jpg" alt="Pose estimation project preview">
```

## Enabling GitHub Pages

1. Push this repository to GitHub.
2. Open the repository on GitHub.
3. Go to **Settings**.
4. In the left sidebar, open **Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch.
7. Select the root folder `/`.
8. Save.

## Deploying From the Main Branch

After GitHub Pages is enabled, deploy updates by committing and pushing changes to `main`:

```bash
git add index.html styles.css script.js assets README.md
git commit -m "Update portfolio website"
git push origin main
```

GitHub Pages will rebuild the site automatically after each push.
