# Pactus website

This repository contains all the content of [https://coderealm33](https://coderealm33) website.


## Running Locally

Install [Jekyll](https://jekyllrb.com/docs/installation/) first. Jekyll is a simple static site generator.

Then clone this repository and running it locally by these commands:

```zsh
git clone https://github.com/pactus-project/coderealm33.git
cd coderealm33
bundle install
bundle exec jekyll serve
```

## Additional commands (Optional)

There are some additional commands that help you to check and improve your changes.
First you need Install [yarn](https://yarnpkg.com/).

Commands:
- Format all markdown and HTML files:
  `yarn run prettier`:

- Remove all metadata from png files by running this command:
  `yarn run exif`

- Check the broken links:
  `htmlproofer --ignore-status-codes "999,429" --check_internal_hash=false --enforce-https=false ./_site`

- Linting markdown files:
  `mdl --style=.mdlrc.rb ./website`

## Deployment

Updating main branch will automatically deploy this repository through github actions.
