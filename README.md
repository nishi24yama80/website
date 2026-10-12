# Tomoki Nishiyama's website

Personal academic website built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template and hosted on GitHub Pages at https://nishi24yama80.github.io/website/.

* Sidebar and site settings: `_config.yml`
* Header menu: `_data/navigation.yml`
* Pages: `_pages/about.md` (home), `_pages/research.md`, `_pages/cv.md`
* PDFs (papers, CV): put them in `files/`
* Profile photo: replace `images/profile.png`

Pushing to `main` builds and deploys the site through `.github/workflows/jekyll.yml`.

To preview locally

```
bundle install
bundle exec jekyll serve -l -H localhost
```
