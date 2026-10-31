## Theodore Rogalski — personal website

Live at https://theohrogalski.github.io/theohrogalski_website/

Built with Jekyll and served by GitHub Pages directly from `main` (no build step).

### Updating content
Everything on the page comes from the YAML files in `_data/`:

| File | Section |
|---|---|
| `news.yml` | News (newest first; first 5 shown) |
| `publications.yml` | Publications |
| `experience.yml` | Research (`category: research`) and Industry (`category: industry`) |
| `projects.yml` | Projects |
| `profile.yml` | Education, honors, leadership, skills |

Name, tagline, links and analytics live in `_config.yml`. The bio text is in `index.html`.

Add an `image:` (jpg/png/gif/mp4/webm in `assets/img/`) to any publication, research or
project entry to show a teaser on the left. To update the CV, replace
`assets/pdf/Theodore_Rogalski_CV.pdf` and keep the same filename.

### Local preview
    bundle install && bundle exec jekyll serve
    # or, with Docker:
    docker run --rm -p 4000:4000 -v "$PWD":/srv/jekyll jekyll/jekyll:pages jekyll serve

Thanks to [Willian Justen](https://github.com/willianjusten/will-jekyll-template), [Vincent Garreau](https://github.com/VincentGarreau/particles.js/), [Jon Barron](https://jonbarron.info), and [Deepak Pathak](https://www.cs.cmu.edu/~dpathak/) for formatting inspiration.
