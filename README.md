# blog-theme

A cool blog theme

## Configuration

The config below is in `.toml` for consistency.

### Author

Sitewide author configuration happens in `config.yaml/toml/json`. The front
matter overrides site configuration.

#### Name

The author name on a post(s).

```toml
[Author]
    name = "John Smith"
```

#### Username

The username on a posts(s).

```toml
[Author]
    name = "John Smith"
    username = "johnsmith"
```

#### URL

The author's URL on a post(s).

```toml
[Author]
    name = "John Smith"
    username = "johnsmith"
    url = "https://example.com"
```

#### Biography

A short message about the author. Can be occupation, biography, etc.

```toml
[Author]
    name = "John Smith"
    username = "johnsmith"
    url = "https://example.com"
    bio = "Author"
```

### Description

The description informs users about the content and should be a short, relevant
summary of the post/site. It can be in the front matter or in the site
configuration.

```toml
[params]
    description = "John Smith's Blog"
```

### Footer

The footer is displayed at the bottom of every page. It defaults to
`this is a footer`. It can only be defined at the site level.

```toml
[params]
    footer = "© 2021 John Smith"
```

### Custom JavaScript

Custom JavaScript modules can be included for additional interactivity.

```toml
[params]
    script = "/scripts/script.js"
```

### Table of Contents

Hugo can automatically generate a table of contents, and users can configure
options in the sitewide configuration.

```toml
[markup]
  [markup.tableOfContents]
    endLevel = 6
    ordered = false
    startLevel = 2
```

To insert the table of contents, users use this shortcode:

    {{< table_of_contents >}}