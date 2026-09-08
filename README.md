# LAARD website repository

Welcome to the repository for the website of the [LAARD Community](https://laardcommunity.github.io/)!

This website is powered by [GitHub Pages](https://docs.github.com/en/pages) & [Jekyll](https://jekyllrb.com/),
using a custom theme based on [Hydeout](https://github.com/fongandrew/hydeout).

## Submissions

This website is principally the responsibility of the
[LAARD Webmaster](https://laardcommunity.github.io/Steering-Committee/), though we welcome and encourage submissions from LAARD
members via Pull Requests or contacting the [Steering Committee](https://laardcommunity.github.io/Steering-Committee/)
via [Element](https://matrix.to/#/#laard:archaeo.social) or [email](laard.community@gmail.com).

### Advanced development

#### Setting up

- Following the [Jekyll installation guides](https://jekyllrb.com/docs/installation/), install Ruby, RubyGems and the
Jekyll Bundler
- Clone this repository (either fork it first or we can add you as a collaborator)
- Make any changes on a new branch
- Run `bundle exec jekyll serve` to build the site locally and check everything's working
- Commit and push to your fork/branch
- Submit a Pull Request to merge changes onto Main

#### Adding content

- Most new content should be in the form of Posts or Events, created by adding new Markdown files in either `/_posts`
or `_events` respectively
  - The file names for these should be in the form `<YYYY>-<MM>-<DD>-<post-title>.md`
- Other pages can be modified using their respective Markdown or HTML files
- New translations of the About page should be Markdown files placed in the `/about` directory
- The homepage content is set by `main.html`
