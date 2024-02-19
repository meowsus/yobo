# Install

## Install Git

https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

## Clone Project

```sh
git clone https://github.com/meowsus/yobo.git ~/path/to/yobo
```

## Install Dependencies

Install some prerequisite dependencies:

- [Ruby](https://github.com/rbenv/ruby-build/wiki#suggested-build-environment)
- [Node](https://github.com/nodejs/node/blob/main/BUILDING.md#building-nodejs-on-supported-platforms)

## Install asdf

https://asdf-vm.com/guide/getting-started.html#_5-install-a-version

## Add asdf plugins

```sh
asdf plugin add ruby https://github.com/asdf-vm/asdf-ruby.git
asdf plugin add nodejs https://github.com/asdf-vm/asdf-nodejs.git
```

## Install `ruby` and `nodejs`

```sh
cd ~/path/to/yobo
asdf install
```

# Running the server

```sh
bundle exec jekyll serve --livereload
```

# Formatting files

```sh
npm run prettier:write
```
