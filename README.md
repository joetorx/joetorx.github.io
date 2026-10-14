# joetorx.github.io

Source of my personal GitHub Pages website.

## Local setup

```sh
bundle install
```

See `.ruby-version` file for Ruby version.

## Local preview

```sh
bundle exec jekyll serve
```

## Content structure

* `_posts` - blog posts go here
* `_data/projects.yml` - projects go here

### Project entry format

```
- name: <project name>
  description: <short description>
  repo: <github repo name>
```
