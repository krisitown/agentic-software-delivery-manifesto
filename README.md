# Software delivery in the age of AI

A single-page manifesto. Plain HTML and CSS, with no build step, JavaScript, analytics, or external font dependencies.

## Local preview

Run a static web server in this directory, then open its local address. For example:

```sh
python3 -m http.server 8080
```

## GitHub Pages

For a dedicated repository, put the contents of this directory at the repository root and commit them. In the repository settings, open **Pages**, choose **Deploy from a branch**, and select the publishing branch and **/(root)**. GitHub displays the published address there after deployment.

For an existing repository that publishes a `docs` directory, put these files inside that directory and select **/docs** instead. Preserve any existing site unless replacing it is intended.

The `.nojekyll` file keeps this a plain static site. Relative asset links support both user and project Pages URLs. The page is ready to publish; these instructions do not imply that a repository or deployment has already been created.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Editing

Edit `index.html` for the text and `style.css` for its appearance. The manifesto is an independent perspective, not an endorsement by the authors in the reading list. Add the desired author attribution before publishing if wanted.
