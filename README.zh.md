<div align="center">

# haru-skills

**haru 的 Claude Code 插件市场**

面向 Claude Code 的技能 · 插件合集 — 按需挑选安装。

[![License: MIT](https://img.shields.io/badge/License-MIT-black.svg)](./LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Plugin%20Marketplace-d97706)](https://docs.claude.com/en/docs/claude-code/plugins)
[![Plugins](https://img.shields.io/badge/plugins-1-blue)](#插件列表)
[![GitHub stars](https://img.shields.io/github/stars/bluei98/haru-skills?style=social)](https://github.com/bluei98/haru-skills)

[English](./README.md) · [한국어](./README.ko.md) · [日本語](./README.ja.md) · **中文**

</div>

---

## 快速开始

在 Claude Code 中执行以下两行即可完成安装。

```bash
# 1. 添加插件市场（仅首次）
/plugin marketplace add bluei98/haru-skills

# 2. 安装想要的插件
/plugin install domain-search@haru-skills
```

> [!NOTE]
> Claude Code 插件系统要求使用 `<plugin>@<marketplace>` 格式的安装语法。
> 请务必加上 `@haru-skills` 后缀。

---

## 插件列表

<table>
<thead>
<tr>
<th>插件</th>
<th>说明</th>
<th>安装命令</th>
<th>源仓库</th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="./plugins/domain-search"><code>domain-search</code></a></td>
<td>品牌命名 + 基于 whois 的域名可用性检查</td>
<td><code>/plugin install domain-search@haru-skills</code></td>
<td><a href="https://github.com/bluei98/domain-search">bluei98/domain-search</a></td>
</tr>
</tbody>
</table>

---

## 贡献 · 问题

- Bug / 建议: [GitHub Issues](https://github.com/bluei98/haru-skills/issues)
- 各插件相关问题请提交到对应插件的仓库。

## 许可证

插件市场本身: **MIT**
每个插件遵循其自身仓库的许可证。

<div align="center">

Made with care by [**@bluei98**](https://github.com/bluei98)

</div>
