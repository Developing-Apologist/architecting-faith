# Architecting Faith Presentation

This presentation is formatted in Markdown and can be viewed using various presentation tools. Here are some options:

## Using mkslides

1. Install mkslides:
```bash
pip install mkslides
```

2. Build the presentation:
```bash
mkslides build slides.md
```

3. Serve the presentation locally:
```bash
mkslides serve slides.md
```

4. Open the presentation in your browser:
```bash
open _site/slides.html
```

## Using Marp

1. Install Marp:
```bash
npm install -g @marp-team/marp-cli
```

2. Convert to PDF:
```bash
marp slides.md --pdf
```

3. Convert to HTML:
```bash
marp slides.md --html
```

## Using Slidev

1. Install Slidev:
```bash
npm init slidev@latest
```

2. Copy the contents of `slides.md` into your Slidev project.

## Presentation Structure

The presentation consists of 13 slides covering:
1. Title Slide
2. Big Idea
3. The Drift Problem
4. Faith System Blueprint
5. Environment Setup
6. CI/CD for the Soul
7. Monitoring & Alerts
8. Incident Response Plan
9. Scaling Faith
10. Common System Failures
11. Spiritual CI/CD Plan
12. Final Challenge
13. Thank You / Connect

## Customization

You can customize the presentation by:
- Replacing the placeholder images with your own
- Adjusting the theme colors in the YAML frontmatter
- Adding your own social media handles and QR code
- Modifying the content to better suit your audience 