<div align="center">

# haru-skills

**haru の Claude Code プラグインマーケットプレイス**

Claude Code 向けのスキル・プラグイン集 — 必要なものだけを選んでインストール。

[![License: MIT](https://img.shields.io/badge/License-MIT-black.svg)](./LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Plugin%20Marketplace-d97706)](https://docs.claude.com/en/docs/claude-code/plugins)
[![Plugins](https://img.shields.io/badge/plugins-1-blue)](#プラグイン一覧)
[![GitHub stars](https://img.shields.io/github/stars/bluei98/haru-skills?style=social)](https://github.com/bluei98/haru-skills)

[English](./README.md) · [한국어](./README.ko.md) · **日本語** · [中文](./README.zh.md)

</div>

---

## クイックスタート

Claude Code で次の 2 行だけでインストール完了。

```bash
# 1. マーケットプレイスを登録（初回のみ）
/plugin marketplace add bluei98/haru-skills

# 2. 好きなプラグインをインストール
/plugin install domain-search@haru-skills
```

> [!NOTE]
> Claude Code のプラグインシステムは `<plugin>@<marketplace>` 形式のインストール構文を要求します。
> `@haru-skills` を必ず付けてください。

---

## プラグイン一覧

<table>
<thead>
<tr>
<th>プラグイン</th>
<th>説明</th>
<th>インストール</th>
<th>ソースリポジトリ</th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="./plugins/domain-search"><code>domain-search</code></a></td>
<td>ブランドネーミング + whois によるドメイン利用可否チェック</td>
<td><code>/plugin install domain-search@haru-skills</code></td>
<td><a href="https://github.com/bluei98/domain-search">bluei98/domain-search</a></td>
</tr>
</tbody>
</table>

---

## コントリビュート・Issue

- バグ / 提案: [GitHub Issues](https://github.com/bluei98/haru-skills/issues)
- 各プラグイン固有の Issue は、該当プラグインのリポジトリへお願いします。

## ライセンス

マーケットプレイス本体: **MIT**
各プラグインは、それぞれのリポジトリのライセンスに従います。

<div align="center">

Made with care by [**@bluei98**](https://github.com/bluei98)

</div>
