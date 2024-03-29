# jekyll-theme-console

change text

## Demo

[https://b2a3e8.github.io/jekyll-theme-console/](https://b2a3e8.github.io/jekyll-theme-console/)

source code: [https://github.com/b2a3e8/jekyll-theme-console/tree/gh-pages](https://github.com/b2a3e8/jekyll-theme-console/tree/gh-pages)


## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "jekyll-theme-console"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: jekyll-theme-console
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install jekyll-theme-console

## Usage

In addition to jekyll's default configuration options, you can provide:
- `header_pages` to specify which pages should be displayed in navbar
- `footer` string, which will be inserted on the end of the page (doesn't support markup, but html)
- `google_analytics` tracking id (tracking will be enabled only in production environments)
- `listen_for_clients_preferred_style` boolean, used to allow users to choose theme based on their preferences (mostly affected by OS dark or light theme, details see https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme)

```yaml
header_pages:
  - index.md
  - about.md

style: dark # dark (default) or light
listen_for_clients_preferred_style: true # true or false (default)

footer: 'follow us on <a href="https://twitter.com/xxx">twitter</a>'

google_analytics: UA-NNNNNNNN-N
```

## Customization

If you want to customize this theme, follow this steps:
1. Fork this repository (you can use the fork as your own theme or directly as your website)
2. Create or modify files in `_layouts` directory for html-based changes
3. Create or modify files in `_sass` and `assets` for css-based changes
   - You can change things which are used in light and dark theme (like font-size) in `_sass/base.scss`. You'll find style variables at the top.
   - Style-specific definitions are in `_sass/_dark.scss` respectively in `_sass/_light.scss`. You can change things like background-color there.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/b2a3e8/jekyll-theme-console. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `jekyll-theme-console.gemspec` accordingly.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
