# Vienna

## Overview

Vienna is a simple and clean blog theme for [Hugo](http://gohugo.io/).
Notable features are:

- Simple and clean design
- Client side source code highlighting
- Social links (Twitter, Facebook, GitHub, LinkedIn)
- Support for tags
- Analytics with Google Analytics or Mixpanel
- Responsive design
- Font Awesome icons

## Installation

In your hugo site directory, run:

```shell
$ mkdir themes
$ cd themes
$ git clone https://github.com/keichi/vienna
```

## Configuration

You may specify following options in `config.toml` of your site to make use of
this theme's features.

```toml
baseurl = "Your site URL"
languageCode = "en-us"
title = "Your site title"
# Copyright notice. This is displayer in the footer.
copyright = "&copy; Copyright notice"

[params]
    # Social accounts. Link to these accounts are displayed in the header and
    # footer.
    twitter = "Your Twitter username"
    github = "Your GitHub username"
    linkedin = "Your LinkedIn username"
    googleplus = "Your Google+ user id"
    facebook = "Your Facebook username"
    stackoverflow = "Your Stackoverflow user id (number)"
    # Google Analytics API key.
    ga_api_key = "Your Google Analytics tracking id"
    # Mixpanel API key.
    mixpanel_api_key = "Your Mixpanel API key"
    author = "Your Name"
    avatar = "/path/to/avatar"
    contact = "Your contact link (ex. mailto:foo@example.com)"
    bio = "Your short bio/tagline"
    # Short subtitle/tagline. This is displayed in the header.
    subtitle = "is a software developer, hardware hacker and a beer lover. He believes in the power of code."
    themecolor = "#hexcolor" # Defines the tab color in Chrome for Android.
```

## Usage

Use hugo's `-t vienna` or `--theme=vienna` option with hugo commands.
Example:

```shell
$ hugo server -t vienna -w -D
```

