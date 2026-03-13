# CV — Igor Šinkovec

Hosted at [sinkovec.cc/cv](https://sinkovec.cc/cv)

Built with [online-cv](https://github.com/sharu725/online-cv) Jekyll theme.

## Setup

### 1. Fork or clone this repo into your GitHub account

### 2. Enable GitHub Pages
- Go to repo **Settings → Pages**
- Set source to **gh-pages** branch (created automatically by the workflow)

### 3. Point your domain
In your DNS provider (for `sinkovec.cc`), add:
```
CNAME  cv  igorsinkovec.github.io
```
Then in repo Settings → Pages → Custom domain, enter: `sinkovec.cc/cv`

### 4. Add your photo
Place a square photo named `profile.jpg` in `/assets/images/`

### 5. Edit your CV
All content lives in `_data/data.yml`. Edit there only.

### 6. Color scheme
Change `theme_skin` in `_config.yml`:
Options: `blue` · `turquoise` · `green` · `berry` · `orange` · `ceramic`

## PDF
A PDF is auto-generated on every push to `main` and available at:
`https://sinkovec.cc/cv/igor-sinkovec-cv.pdf`

## Local preview
```bash
bundle install
bundle exec jekyll serve
# open http://localhost:4000/cv
```
