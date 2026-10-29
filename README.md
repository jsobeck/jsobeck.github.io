# jsobeck.github.io

Personal website of Jennifer Sobeck: <https://jsobeck.github.io>

Built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template
and deployed by GitHub Actions (`.github/workflows/jekyll.yml`) on every push to `main`.
In the repository settings, **Settings > Pages > Source** must be set to **GitHub Actions**.

## Where things live
- Site settings, sidebar profile and social links: `_config.yml`
- Header menu: `_data/navigation.yml`
- Pages: `_pages/` (`about.md` is the home page)
- Profile photo: `images/profile.jpg`
- CV PDF: `files/JSobeck_CV.pdf`

## Local preview
```
bundle install
bundle exec jekyll serve -l -H localhost
```
