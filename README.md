# Weiqin Jiao's academic homepage

Personal academic website based on [academic-homepage](https://github.com/luost26/academic-homepage).

## Content

- Home: biography, research interests, news, selected publications, and academic background.
- Publications: published papers and a separate section for manuscripts under review.
- Teaching & Service: teaching, supervision, reviewing, presentations, and honours.

Edit personal details in `_data/profile.yml`, publication records in `_publications/`, and news in `index.html`. Add a `cover` path to a publication record when its illustration is ready.

## GitHub Pages

Repository: `HeinzJiao/heinzjiao.github.io`. Website: https://heinzjiao.github.io/

In the repository's Pages settings, select **GitHub Actions** as the publishing source. The workflow in `.github/workflows/pages.yml` builds the site with Jekyll and deploys pushes to `main`.

The source uses an empty `baseurl` for the account's root website. The previous `academic-homepage` repository redirects old page URLs to this site.

Personal content is stored in YAML and Markdown; layouts and appearance are defined by the HTML templates and CSS.

## Credits

Template by Shitong Luo, distributed under the MIT license. Bootstrap is distributed under its MIT license.

