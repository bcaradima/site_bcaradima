# Readme
Website adapted from the [Avicenna theme](https://github.com/hadisinaee/avicenna) for Hugo. The Avicenna theme is in turn adapted from the [Academic theme](https://themes.gohugo.io/themes/hugo-academic/).

Minor changes to the Avicenna theme include:

- disabled news, blog, and CV for now
- changed the Academia header to Education (edit: `themes/avicenna/layouts/partials/about/interests_academia.html`)
- improved the presentation of the education items
- modified the affiliations
- adjusted color scheme in `/themes/avicenna/static/css/style.css`

## Items

- maybe add news? for instance:
https://www.eawag.ch/en/news-agenda/news-portal/news-detail/improved-health-check-for-running-waters/
- add projects
- change red color of headers in `style.css`

## Usage
`site_bcaradima` is where the website content is edited and updated. Build the website and deploy it to `/site_bcaradima/docs`, then commit static website files in `docs` to `bcaradima.github.io`.

Content: ~/site_caradima/content/about/_index.md

* edit `content` as needed, commit and push changes from git repo in `site_bcaradima`
* `cd` into `site_bcaradima`
* run `hugo`
* `cd` into `docs` where static content is updated
* note there is a git repo in `site_bcaradima` and `docs`
* use `docs` git to commit changes (`git commit -m "message"`) to static content and push changes to `bcaradima.github.io` (`git push origin master`)
* note some updates can take time due to GitHub Pages
