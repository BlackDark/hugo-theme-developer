# BlackDark Developer Theme

- Base: https://github.com/xriley/Developer-Theme
- Motivation: https://github.com/ineesalmeida/almeida-cv

# Usage
## Install Hugo (extended)
To use `blackdark-developer-theme` theme you need to install Hugo Extended by following https://gohugo.io/getting-started/installing/.

## Create your personal website
```
hugo new site <your website's name>
cd <your website's name>
git init
git submodule add https://github.com/BlackDark/hugo-theme-developer.git themes/blackdark-developer-theme
```
Replace the files in your site root's directory with the ones in `themes/blackdark-developer-theme/exampleSite`.

## Start Hugo in development mode
```
hugo server -D
```
Your site is now available at http://localhost:1313/.

## Customization
Your professional data should be added in the `data/content.yaml` file. You can change the theme colors and number of
pages in the `config.toml` file. For working example, see `exampleSite` directory.

For more advanced customization, in your site root directory create `assets/scss/_custom.scss` file where you can
overwrite theme SCSS as per your liking.

## Building
To generate static files of your website, execute the following:
```
hugo --minify
```
within the root of your project.

# Contributing
Post bugs and contributions to the issue tracker. Or make a pull request.
