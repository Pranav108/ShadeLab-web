# ShadeLab website

Official ShadeLab game website, support and privacy policy.

- Website:https://pranav108.github.io/ShadeLab-web/
- Privacy:https://pranav108.github.io/ShadeLab-web/privacy/
- Support:https://pranav108.github.io/ShadeLab-web/support/
- Contact:pranvcoder@gmail.com

## Publishing

GitHub Pages publishes the repository root from `main`. `.nojekyll` keeps the static HTML/CSS/assets unchanged. Push to `main` to update the website. No ChatGPT hosting, server runtime, package installation, analytics or third-party font requests are required.

Run `python3 build-pages.py` after editing page content;commit the generated HTML and push. Styles and images live in `styles.css` and `assets/`. Internal URLs use `/ShadeLab/` for GitHub Pages project hosting. Update `origin` and `base_path` in the generator if moving to a different path/domain.

The images are approved game artwork and actual simulator captures. Nunito font license is in `assets/Nunito-OFL.txt`. The Unity app, signing files and player saves are not part of this website repository.
