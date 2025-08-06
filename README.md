# Minimal Mistakes remote theme starter

Click [**Use this template**](https://github.com/mmistakes/mm-github-pages-starter/generate) button above for the quickest method of getting started with the [Minimal Mistakes Jekyll theme](https://github.com/mmistakes/minimal-mistakes).

Contains basic configuration to get you a site with:

- Sample posts.
- Sample top navigation.
- Sample author sidebar with social links.
- Sample footer links.
- Paginated home page.
- Archive pages for posts grouped by year, category, and tag.
- Sample about page.
- Sample 404 page.
- Site wide search.

Replace sample content with your own and [configure as necessary](https://mmistakes.github.io/minimal-mistakes/docs/configuration/).

---

## Troubleshooting

If you have a question about using Jekyll, start a discussion on the [Jekyll Forum](https://talk.jekyllrb.com/) or [StackOverflow](https://stackoverflow.com/questions/tagged/jekyll). Other resources:

- [Ruby 101](https://jekyllrb.com/docs/ruby-101/)
- [Setting up a Jekyll site with GitHub Pages](https://jekyllrb.com/docs/github-pages/)
- [Configuring GitHub Metadata](https://github.com/jekyll/github-metadata/blob/master/docs/configuration.md#configuration) to work properly when developing locally and avoid `No GitHub API authentication could be found. Some fields may be missing or have incorrect data.` warnings.

## Development cycle

I run the site locally so I can preview changes before publishing them. Instructions for setting up your development environment can be found on the Jekyll site linked above.

To start the server and watch for code changes, I run the following command from the root directory in Bash:

```bash
bundle exec jekyll serve -l
```
There are two parts here:

1. bundle exec, which ensures only the gems listed in the Gemfile are used.
2. jekyll serve -l, which starts the local server with live reload enabled.

This allows the server to regenerate static pages automatically when a file changes. It’s not perfect, but it works well most of the time.

## Production deployment
Site changes are published by pushing to the main branch, which automatically triggers GitHub Actions. There are many blog posts available that explain how to set this up in detail.

