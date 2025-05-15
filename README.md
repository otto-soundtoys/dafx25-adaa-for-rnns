# DAFx25 - Antiderivative Antialiasing for Recurrent Neural Networks

This repo contains the accompanying webpage for the DAFx25 paper *"Antiderivative Antialiasing for Recurrent Neural Networks"*

## Development

### Setup

Requires:
- Jekyll
  - Ruby
  - RubyGems
  - GCC & Make

See https://jekyllrb.com/docs/installation/

### Usage

Host locally
```bash
bundle exec jekyll serve --livereload
```

Updated `Gemfile`? Run
```bash
bundle install
```

Edited `_config.yml`? Restart webserver (above).

Check gem info
```bash
bundle info <GEM> <OPTARGS>
```

Workflow: Check gem-based theme properties
```bash
tree $(bundle info --path <GEM>) -L 2
```

