## KIPBOK Project
KiP Body of Knowledge

## Project environment
- install bundler and jekyll
- git clone https://github.com/toacy/kipbok.git
- cd kipbok
- bundle exec jekyll serve (http://localhost:4000)

## Running with docker
- git clone https://github.com/toacy/kipbok.git
- cd kipbok
- docker run --rm --volume="$PWD:/srv/jekyll" -it jekyll/jekyll:latest jekyll build
- docker run --rm --volume="$PWD:/srv/jekyll" -p 4000:4000 jekyll/jekyll:latest jekyll serve
- (http://localhost:4000)

## To browse the site go to:
https://toacy.github.io/kipbok/