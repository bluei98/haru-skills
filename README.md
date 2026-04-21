<div align="center">

# haru-skills

**haru's Claude Code Plugin Marketplace**

A curated collection of skills and plugins for Claude Code — install only what you need.

[![License: MIT](https://img.shields.io/badge/License-MIT-black.svg)](./LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Plugin%20Marketplace-d97706)](https://docs.claude.com/en/docs/claude-code/plugins)
[![Plugins](https://img.shields.io/badge/plugins-1-blue)](#plugins)
[![GitHub stars](https://img.shields.io/github/stars/bluei98/haru-skills?style=social)](https://github.com/bluei98/haru-skills)

**English** · [한국어](./README.ko.md) · [日本語](./README.ja.md) · [中文](./README.zh.md)

</div>

---

## Quick Start

Two lines in Claude Code and you're done.

```bash
# 1. Register the marketplace (one-time)
/plugin marketplace add bluei98/haru-skills

# 2. Install the plugin you want
/plugin install domain-search@haru-skills
```

> [!NOTE]
> Claude Code's plugin system requires the `<plugin>@<marketplace>` install syntax.
> Don't forget the `@haru-skills` suffix.

---

## Updating

When the marketplace or a plugin gets updated, pull the latest inside Claude Code:

```bash
# 1. Refresh the marketplace catalog
/plugin marketplace update haru-skills

# 2. Reload installed plugins so changes take effect
/reload-plugins
```

---

## Plugins

<table>
<thead>
<tr>
<th>Plugin</th>
<th>Description</th>
<th>Install</th>
<th>Source Repo</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>domain-search</code></td>
<td>Brand naming + whois-based domain availability check</td>
<td><code>/plugin install domain-search@haru-skills</code></td>
<td><a href="https://github.com/bluei98/domain-search">bluei98/domain-search</a></td>
</tr>
</tbody>
</table>

---

## Contributing · Issues

- Bugs / suggestions: [GitHub Issues](https://github.com/bluei98/haru-skills/issues)
- Plugin-specific issues should go to the respective plugin's repository.

## License

Marketplace itself: **MIT**.
Each plugin follows the license of its own repository.

<div align="center">

Made with care by [**@bluei98**](https://github.com/bluei98)

</div>
