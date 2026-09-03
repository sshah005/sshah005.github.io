# Syed Sadman Shahriar — GitHub Pages Portfolio

This repository is a clean academic/professional portfolio inspired by the
sidebar + top-navigation structure commonly used by AcademicPages/Minimal
Mistakes academic websites.

## 1. Create the GitHub repository

For a personal GitHub Pages site, create a repository named exactly:

`YOUR-USERNAME.github.io`

Example:

`syedsadmanshahriar.github.io`

Then upload all files from this folder to the repository root.

## 2. Turn on GitHub Pages

In GitHub:

1. Open **Settings**
2. Open **Pages**
3. Under **Build and deployment**, choose **Deploy from a branch**
4. Branch: `main`
5. Folder: `/ (root)`
6. Save

Your site will appear at:

`https://YOUR-USERNAME.github.io/`

## 3. The files you will edit most often

### `_data/profile.yml`
Change:
- name
- title
- university
- profile picture
- LinkedIn
- GitHub
- email
- tagline
- About text

### `_data/navigation.yml`
Controls the navigation bar.

### `index.md`
Home / About page.

### `education.md`
Education history.

### `experience.md`
Work and assistantship history.

### `projects.md`
Projects.

### `awards.md`
Awards and professional development.

### `cv.md`
CV page.

### `contact.md`
Contact page.

## 4. Add your photograph

Put your photo in:

`assets/images/profile.jpg`

Then change this line in `_data/profile.yml`:

```yaml
avatar: "/assets/images/profile.jpg"
```

A square image works best.

## 5. Add your CV

Put the PDF here:

`assets/files/Syed_Sadman_Shahriar_CV.pdf`

Then open `cv.md` and remove the HTML comment markers around the CV button.

## 6. Preview locally (optional)

Install Ruby and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open:

`http://localhost:4000`

You can also simply push changes to GitHub and let GitHub Pages build the site.

## 7. Recommended additions

Once the basic site is live, consider adding:
- GitHub profile
- email
- downloadable résumé/CV
- a professional headshot
- exact employment dates
- relevant coursework
- technical skills
- policy/data tools
- project reports or PDFs
- certifications with credential links

## Notes

The included content uses only publicly visible information and intentionally
leaves unverified personal details as placeholders.
