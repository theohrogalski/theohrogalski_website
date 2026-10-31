## Theodore Rogalski — personal website

Live at https://theohrogalski.github.io/theohrogalski_website/

Built with Jekyll and served by GitHub Pages directly from `main` (no build step)


### Local preview
    bundle install && bundle exec jekyll serve
    # or, with Docker:
    docker run --rm -p 4000:4000 -v "$PWD":/srv/jekyll jekyll/jekyll:pages jekyll serve

Thanks to [Willian Justen](https://github.com/willianjusten/will-jekyll-template), [Vincent Garreau](https://github.com/VincentGarreau/particles.js/), [Jon Barron](https://jonbarron.info), and [Deepak Pathak](https://www.cs.cmu.edu/~dpathak/) for formatting inspiration.
