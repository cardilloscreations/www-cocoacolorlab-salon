# Development & Authoring Content

The instructions below are useful reminders but it's a fairly common workflow for any Jekyll based website.

## System Preparation

To use this project, you'll need the following things installed on your machine.

1. [Jekyll](http://jekyllrb.com/docs/) - `$ gem install jekyll bundler`
2. [Jekyll-Gems](http://jekyllrb.com/docs/) - `$ bundle install`


## Usage

Since this is a Jekyll site, every command described in the [Jekyll documentation](https://jekyllrb.com/docs/) is available.

### Development

To start the development workflow, run:

```
bundle exec jekyll serve --livereload
```

### Production

To build the project, run:

```
bundle exec jekyll build
```

### GitHub Pages

Because this site is using the latest version of Jekyll, deployment to GitHub Pages must happen by way of a custom Workflow Action.

For more information see: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#publishing-with-a-custom-github-actions-workflow
