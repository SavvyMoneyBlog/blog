# Blog
[The Savvy Money Blog](https://savvymoneyblog.github.io/blog/)

## Development

If this is your first time, do Setup first

### Running locally

```rb
bundle exec jekyll serve
```

### Setup

1. Install Ruby

```sh
sudo apt install ruby-full build-essential zlib1g-dev
```

2. Ensure env vars are set correctly

These should be specified in `.bashrc` or equivalent.

```
export GEM_HOME=$HOME/.gem
export GEM_PATH=$HOME/.gem
```

2. Install Jekyll

```rb
gem install jekyll bundler
```

3. Test locally

If setting up for first time:
```rb
$ jekyll new --skip-bundle --force .
```

To install needed dependencies.
```rb
$ bundle install
```

Running locally
```rb
bundle add webrick
```

### Tips

[Customizing the site](https://jekyllrb.com/docs/themes/#overriding-theme-defaults)
[Customizing Merlot theme specifically](https://github.com/pages-themes/merlot)
Each custom layout should specify its parent layout in its header, likely until the parent is `default` (which is automatically supplied by the theme)

Make sure the post date/time are not in the future. They won't show up until the site is generated after that date/time.

## AI prompt

> Let's write a personal finance blog. Will you write the [first] post about [topic]?