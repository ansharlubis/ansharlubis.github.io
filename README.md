# Local install

## Prerequisites

- Ruby
- Bundler

## Installation

```bash
bundle install
bundle exec jekyll serve
```

# Adding a new page

1. Add the markdown file, e.g. `diary.md`

2. Put posts under `/_diary`

3. Add the following to `config.yml`

```
collections:
  diary:
    output: true
    permalink: /diary/:name/
```