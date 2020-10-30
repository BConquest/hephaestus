# hephaestus
Hephaestus is a portfolio theme for zola. It uses bulma css and supports using icons from ion-icon.

![hephaestus screenshot]("https://raw.github.com/BConquest/hephaestus/blob/main/hephaestus.png")

## Contents
- [Installation](#installation)
- [Options](#options)
	- [Navigation Bar](#navigation-bar)
	- [Education](#education)
	- [Projects](#projects)
	- [Skills](#skills)
	- [Social Links](#social-links)

## Installation

First, you will download the theme into your `themes` directory:

```bash
$ cd themes
$ git clone https://github.com/BConquest/hephaestus
```

Second, you will enable the theme in your `config.toml` directory:

```toml
theme = "hephaestus"
```

## Options
### Navigation Bar
To edit the navigation bar you will need to edit your `config.toml` to include:

```toml
menu = [
{ text = "foo", link = "/foo"},
{ text = "bar", link = "/bar"},
]
```
You can have as many items as you want to have and the links can be to anything.

### Education

# TODO

### Projects
To edit the projects that are displayed you will need to create a directory in `content`.
In the `_index.md` the frontmatter needs to include:

```TOML
+++
title = "foo"
template = "projects.html"

[extra]
author = "bar"
```

Then for every project you want to add you will need to format the `*.md` as:

```md
+++
title = "foo"

[extra]
image = "/image_location"
link = "link to project"
technologies = ["bar", "baz"]
+++

Description of project named foo.
```

### Skills
### Social Links

