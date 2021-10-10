# blog-theme

A cool blog theme

## Configuration

The config below is in `.toml` for consistency.

### Author

Sitewide author configuration happens in `Config.yaml/toml/json`. The front matter overrides site configuation.

#### Name

The author name on a post(s).

```
[Author]
name = "John Smith"
```

#### Username

The username on a posts(s).

```
[Author]
name = "John Smith"
username = "johnsmith"
```

#### URL

The author's URL on a post(s).

```
[Author]
name = "John Smith"
username = "johnsmith"
url = "https://example.com"
```

#### Biography

A short message about the author. Can be occupation, biography, etc.

```
[Author]
name = "John Smith"
username = "johnsmith"
url = "https://example.com"
bio = "Author"
```

### Description

The description informs users about the content and should be a short, relevant summary of the post/site. It can be in the front matter or in the site configuration.

```
[params]
description = "John Smith's Blog"
```

### Footer

The footer is displayed at the bottom of every page. It defaults to `this is a footer`. It can only be defined at the site level.

```
[params]
footer = "© 2021 John Smith"
```

### Custom JavaScript

Custom JavaScript modules can be included for additional interactivity.

```
[params]
script = "/scripts/script.js"
```
