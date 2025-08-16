<div align="center">
  <br>

  <h1>📚 GLOSSARY</h1>
  <h3>Cybersecurity Glossary & Reference Platform</h3>

</div>

<h4 align="center">
  A comprehensive cybersecurity resource built with <a href="https://jekyllrb.com/" target="_blank"><code>Jekyll</code></a> and the YAT theme.
</h4>

<p align="center">
  <a href="https://jeffreytse.github.io/jekyll-theme-yat">
    <img src="https://github.com/jeffreytse/jekyll-theme-yat/workflows/Github%20Pages/badge.svg"
      alt="Github Pages" />
  </a>

  <a href="https://badge.fury.io/rb/jekyll-theme-yat">
    <img src="https://badge.fury.io/rb/jekyll-theme-yat.svg"
      alt="Gem Version" />
  </a>

  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-brightgreen.svg"
      alt="License: MIT" />
  </a>

  <a href="https://liberapay.com/jeffreytse">
    <img src="https://img.shields.io/liberapay/goal/jeffreytse.svg?logo=liberapay"
      alt="Donate (Liberapay)" />
  </a>

  <a href="https://patreon.com/jeffreytse">
    <img src="https://img.shields.io/badge/support-patreon-F96854.svg?style=flat-square"
      alt="Donate (Patreon)" />
  </a>

  <a href="https://ko-fi.com/jeffreytse">
  <img height="20" src="https://www.ko-fi.com/img/githubbutton_sm.svg"
  alt="Donate (Ko-fi)" />
  </a>
</p>

<div align="center">
  <sub>Built with ❤︎ by
  <a href="mailto:omarhadyabass@gmail.com">Omar Alnajjar</a> | 
  Based on <a href="https://github.com/jeffreytse/jekyll-theme-yat">Jekyll YAT Theme</a>
  </sub>
</div>

<br>

Welcome to **GLOSSARY**, your comprehensive cybersecurity glossary. This platform is dedicated to 
providing clear definitions, practical examples, and comprehensive coverage of cybersecurity concepts. 
**If you're passionate about cybersecurity and want to understand the terminology, tools, and threats, 
you're in the right place.**

<p align="center">
Interested in cybersecurity? Explore GLOSSARY for comprehensive definitions!<br>
Your feedback and collaboration are always welcome.
</p>

<p align="center">

  <img src="https://user-images.githubusercontent.com/9413601/91842897-6a840b00-ec87-11ea-95ca-52abcc1ac063.png" alt="demo-screenshot" width="100%"/>

</p>

<h4 align="center">BANNER</h4>

<p align="center">

  <img src="https://user-images.githubusercontent.com/9413601/123897812-ae729a00-d996-11eb-96b8-b76ba926f555.gif" alt="demo-screenshot" width="100%"/>

</p>

## What We Cover

- 🔒 **Threat Intelligence & Analysis** - Latest cyber threats and attack patterns
- 🛡️ **Vulnerability Research** - CVE analysis and exploitation techniques
- 🛠️ **Security Tools & Techniques** - Hands-on security testing and defense
- 📊 **Incident Response & Forensics** - Digital investigation and analysis
- 🌐 **Network Security** - Penetration testing and network defense
- 📱 **Mobile & IoT Security** - Emerging device security challenges
- ☁️ **Cloud Security & DevSecOps** - Modern infrastructure security
- 🔐 **Cryptography & Privacy** - Encryption and data protection

## Blog Features

- Support beautiful **Night Mode** for comfortable reading
- Modern responsive web design optimized for all devices
- Full layouts: `home`, `post`, `tags`, `archive` and `about`
- Beautiful syntax highlighting for code examples
- Image gallery support for security diagrams and screenshots
- RSS feed for easy content subscription
- SEO optimized for better search engine visibility
- Sitemap support for content discovery
- MathJAX support for technical documentation
- Google Translation support for global accessibility

Also, visit the [Live Demo][yat-live-demo] site for the theme.

## Installation

There are three ways to install:

- As a [gem-based theme](https://jekyllrb.com/docs/themes/#understanding-gem-based-themes).
- As a [remote theme](https://blog.github.com/2017-11-29-use-any-theme-with-github-pages/) (GitHub Pages compatible).
- Forking/directly copying all of the theme files into your project.

### Gem-based Theme Method

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "jekyll-theme-yat"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: jekyll-theme-yat
```

And then execute:

```bash
$ bundle
```

Or install it yourself as:

```bash
$ gem install jekyll-theme-yat
```

### Remote Theme Method with Jekyll Remote Theme Plugin

Remote themes are similar to Gem-based themes, but do not require `Gemfile` changes or whitelisting making them ideal for sites hosted with GitHub Pages.

To install:

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "jekyll-remote-theme", group: :jekyll_plugins
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
# theme: owner/name --> Don't forget to remove/comment the gem-based theme option
remote_theme: "jeffreytse/jekyll-theme-yat"

# Add the following to activate the plugin
plugins:
  - jekyll-remote-theme
```

And then execute:

```bash
$ bundle
```

### Forking/Cloning the project

You need to update the option of github workflow file `.github/workflows/build-jekyll.yml`, especially to ensure the value of `jekyll_baseurl` is correct.

### GitHub Pages without limitation

GitHub Pages runs in `safe` mode and only allows [a set of whitelisted plugins/themes](https://pages.github.com/versions/). **In other words, the third-party gems will not work normally**.

To use the third-party gem in GitHub Pages without limitation:

Here is a GitHub Action named [jekyll-deploy-action](https://github.com/jeffreytse/jekyll-deploy-action) for Jekyll site deployment conveniently. 👍

## Usage

Add or update your available layouts, includes, sass and/or assets.

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_data`, `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `jekyll-theme-yat.gemspec` accordingly.

## Contributing

Issues and Pull Requests are greatly appreciated. If you've never contributed to an open source project before I'm more than happy to walk you through how to create a pull request.

You can start by [opening an issue](https://github.com/jeffreytse/jekyll-theme-yat/issues/new) describing the problem that you're looking to resolve and we'll go from there.

## License

This theme is licensed under the [MIT license](https://opensource.org/licenses/mit-license.php) © JeffreyTse.

<!-- External links -->

[jekyll]: https://jekyllrb.com/
[yat-git-repo]: https://github.com/jeffreytse/jekyll-theme-yat/
[yat-live-demo]: https://jeffreytse.github.io/jekyll-theme-yat/
[jekyll-spaceship]: https://github.com/jeffreytse/jekyll-spaceship
[jekyll-seo-tag]: https://github.com/jekyll/jekyll-seo-tag
[jekyll-sitemap]: https://github.com/jekyll/jekyll-sitemap
[jekyll-feed]: https://github.com/jekyll/jekyll-feed
[highlight-js]: https://github.com/highlightjs/highlight.js
[photoswipe-5]: https://photoswipe.com/
