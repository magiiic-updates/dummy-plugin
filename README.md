# Dummy Plugin

![Stable 0.1.8](https://badgen.net/badge/Stable/0.1.8/00aa00)
![WordPress 4.5 - 6.2.2](https://badgen.net/badge/WordPress/4.5%20-%206.2.2/3858e9)
![Requires PHP 5.6](https://badgen.net/badge/PHP/5.6/7884bf)
![License GPLv2 or later](https://badgen.net/badge/License/GPLv2%20or%20later/aa0000)

Dummy plugin to test package updater. This plugin does nothing except self-updating.

## Description

This is the long description.  No limit, and you can use Markdown (as well as in the following sections).

For backwards compatibility, if this section is missing, the full length of the short description will be used, and
Markdown parsed.

A few notes about the sections above:

- "Contributors" is a comma separated list of wp.org/wp-plugins.org usernames
- "Tags" is a comma separated list of tags that apply to the plugin
- "Requires at least" is the lowest version that the plugin will work on
- "Tested up to" is the highest version that you've *successfully used to test the plugin*. Note that it might work on
higher versions... this is just the highest one you've verified.
- Stable tag should indicate the Subversion "tag" of the latest stable version, or "trunk," if you use `/trunk/` for
stable.

    Note that the `readme.txt` of the stable tag is the one that is considered the defining one for the plugin, so
if the `/trunk/readme.txt` file says that the stable tag is `4.3`, then it is `/tags/4.3/readme.txt` that'll be used
for displaying information about the plugin.  In this situation, the only thing considered from the trunk `readme.txt`
is the stable tag pointer.  Thus, if you develop in trunk, you can update the trunk `readme.txt` to reflect changes in
your in-development version, without having that information incorrectly disclosed about the current stable version
that lacks those changes -- as long as the trunk's `readme.txt` points to the correct stable tag.

    If no stable tag is provided, it is assumed that trunk is stable, but you should specify "trunk" if that's where
you put the stable version, in order to eliminate any doubt.

## Frequently Asked Questions

### A question that someone might have

An answer to that question.

### What about foo bar?

Answer to foo bar dilemma.

## Screenshots

1. This screen shot description corresponds to screenshot-1.(png|jpg|jpeg|gif). Note that the screenshot is taken from
the /assets directory or the directory that contains the stable readme.txt (tags or trunk). Screenshots in the /assets
directory take precedence. For example, `/assets/screenshot-1.png` would win over `/tags/4.3/screenshot-1.png`
(or jpg, jpeg, gif).
2. This is the second screen shot

## Upgrade Notice

### 1.0
Upgrade notices describe the reason a user should upgrade.  No more than 300 characters.

### 0.5
This version fixes a security related bug.  Upgrade immediately.

## Arbitrary section

You may provide arbitrary sections, in the same format as the ones above.  This may be of use for extremely complicated
plugins where more information needs to be conveyed that doesn't fit into the categories of "description" or
"installation."  Arbitrary sections will be shown below the built-in sections outlined above.

## A brief Markdown Example

Ordered list:

1. Some feature
1. Another feature
1. Something else about the plugin

Unordered list:

- something
- something else
- third thing

Here's a link to [WordPress](https://wordpress.org/ "Your favorite software") and one to [Markdown's Syntax Documentation][markdown syntax].
Titles are optional, naturally.

[markdown syntax]: https://daringfireball.net/projects/markdown/syntax
            "Markdown is what the parser uses to process much of the readme file"

Markdown uses email style notation for blockquotes and I've been told:
> Asterisks for *emphasis*. Double it up  for **strong**.

`<?php code(); // goes in backticks ?>`
