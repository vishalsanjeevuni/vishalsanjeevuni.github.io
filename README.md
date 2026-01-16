# Vishal Sanjeevuni - Portfolio

A clean, modern portfolio website for showcasing data analytics projects and professional experience.

## Live Site

Visit: **https://vishalsanjeevuni.github.io**

## Local Development

```bash
# Start local server
python -m http.server 8000 -d docs/

# Open in browser
open http://localhost:8000
```

## Structure

```
docs/
├── index.html      # Main HTML file
├── styles.css      # Styling
├── script.js       # JavaScript functionality
├── about.md        # About section content
├── projects.md     # Projects/portfolio content
├── skills.md       # Technical skills content
├── resume.md       # Resume/experience content
└── assets/         # Images and other assets
    └── profile.jpg # Profile photo
```

## Customization

1. **Personal Info**: Edit `about.md` to update bio and social links
2. **Projects**: Edit `projects.md` to add your data analytics projects
3. **Skills**: Edit `skills.md` to update your technical skills
4. **Resume**: Edit `resume.md` to add your work experience
5. **Styling**: Modify `styles.css` to change colors and fonts
6. **Profile Photo**: Replace `docs/assets/profile.jpg` with your photo

## Deployment

1. Push to a repo named `vishalsanjeevuni.github.io`
2. Go to Settings → Pages → Source: Deploy from branch → `main` → `/docs`
3. Your site will be live at `https://vishalsanjeevuni.github.io`

## Custom Domain (Optional)

1. Add a `CNAME` file in `docs/` with your domain name
2. Configure DNS to point to GitHub Pages

## Features

- Responsive design (mobile-friendly)
- Dark/light theme toggle
- Smooth scrolling navigation
- Markdown content loading
- Project showcase cards
- Timeline-based resume
- Skills grid layout

## Tech Stack

- HTML5 / CSS3 / JavaScript
- No build step required
- No dependencies
