# SIBL Website

Static website for [SIBL](https://github.com/zig-foundry/sibl) built with [Zine](https://zine-ssg.io).

## Development

Requires the `zine` binary (v0.14+) in `PATH`.

```sh
# Live reload server
zine

# Or build a release into public/
zine release -f
```

## Structure

- `content/` — SuperMD pages
- `content/docs/` — three-part documentation section
- `layouts/` — SuperHTML templates
- `layouts/docs.shtml` — docs layout with responsive sidebar and prev/next pager
- `assets/` — CSS and Cascadia Code variable font
- `zine.ziggy` — site configuration

The site uses a dark theme inspired by the Zine and Zig documentation sites, with Cascadia Code for code samples and a slightly refined layout (flex navigation, feature grid, constrained content width).

Getting Started page mirrors the tone and structure of the upstream README.
