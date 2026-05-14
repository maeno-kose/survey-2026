# survey-2026

株式会社idealの2026年度アンケート集約リポジトリ。各アンケートはサブディレクトリで管理し、GitHub Pages経由で公開する。

## 公開URL

| サブディレクトリ | URL | 内容 |
|----------------|-----|------|
| `pocket-shisha/` | https://ideal-trd.github.io/survey-2026/pocket-shisha/ | ポケットシーシャに関するアンケート |

## 構成

```
survey-2026/
├── README.md
└── pocket-shisha/
    └── index.html  ← Google Apps Script (GAS) 連携の静的アンケートフォーム
```

## 仕組み

- 静的HTML + React (CDN) のシングルファイルアンケート
- 回答送信先は Google Apps Script (GAS) Webアプリ
- GitHub Pagesで配信、回答はGAS経由でGoogleスプレッドシートに集約

## 運営

- 所有: 株式会社ideal (ideal-trd)
- 担当: 孔徳遠
- 作成: 2026-05-14
