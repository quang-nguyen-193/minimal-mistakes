# [Minimal Mistakes Jekyll theme](https://mmistakes.github.io/minimal-mistakes/)

My customized blog from Minimal Mistakes Jekyll theme

- setup locally
```
docker run --rm -it --volume="$PWD:/srv/jekyll" --volume="$PWD/vendor/bundle:/usr/local/bundle" --env JEKYLL_ENV=production jekyll/jekyll:4.0 jekyll build
```
- run locally
```
docker run --rm --volume="$PWD:/srv/jekyll" --volume="$PWD/vendor/bundle:/usr/local/bundle" --env JEKYLL_ENV=development -p 4000:4000 jekyll/jekyll:4.0 jekyll serve
```