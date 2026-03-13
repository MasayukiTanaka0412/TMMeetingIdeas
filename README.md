# TMMeetingIdeas — 世界のToastmastersクラブにおける特別例会のアイデア集

世界中のToastmastersクラブが実施した「通常例会ではない特別なイベント」のアイデアを集めたデータ集です。  
GitHub Pages 上でブラウザから閲覧・検索・診断ができます。

## 機能

| ページ | 説明 |
|---|---|
| `index.html` | 全65件のイベントをタグでフィルタしながら一覧表示します。PDFダウンロード・おすすめ診断へのリンクも含まれます。 |
| `recommend.html` | 10問のYes/No質問に答えると、あなたのクラブに合いそうな特別例会アイデアをスコア順に5件提案します。 |
| `specialmeetings.md` | データ本体。クラブ名・イベント名・概要・URL・タグを記録したMarkdownテーブルです。 |
| `specialmeetings.pdf` | `specialmeetings.md` のPDF版。ダウンロードして配布・印刷に利用できます。 |
| `specialmeetings.docx` | `specialmeetings.md` のWord版。 |

## データ概要

- **収録件数**: 65件
- **作成日**: 2026-03-10
- **対象範囲**: 世界各地のToastmastersクラブの開催レポートおよび開催案内（混在）

### 収録タグ（カテゴリ）例

`マイルストーン` / `記念会` / `周年記念` / `ハイキング` / `屋外イベント` / `Speechcraft` / `Speakathon` / `ワークショップ` / `スキル強化` / `オープンハウス` / `オンライン` / `会員拡大` / `国際交流` / `社交` / `懇親` / `アウトリーチ` / `地域イベント` / `就任式` / `テーマ例会` など

## 使い方

### GitHub Pages で閲覧する

リポジトリの GitHub Pages URL をブラウザで開くと、すぐに使えます。

1. **一覧表示** (`index.html`) — タグを複数選択して絞り込み、気になるイベントを探します。
2. **おすすめ診断** (`recommend.html`) — 10問に答えるだけで、自クラブに合うアイデアを自動提案します。
3. **PDFダウンロード** — 一覧ページのボタンから `specialmeetings.pdf` をダウンロードできます。

### ローカルで動かす

```bash
# リポジトリをクローン
git clone https://github.com/MasayukiTanaka0412/TMMeetingIdeas.git
cd TMMeetingIdeas

# 任意のHTTPサーバで配信（例: Python）
python -m http.server 8080
```

ブラウザで `http://localhost:8080` を開いてください。  
> ⚠️ `fetch()` を使用しているため、`file://` プロトコルでは動作しません。必ずHTTPサーバ経由で開いてください。

## ファイル構成

```
TMMeetingIdeas/
├── index.html            # メインページ（一覧・タグフィルタ）
├── recommend.html        # おすすめ診断ページ
├── specialmeetings.md    # データ本体（Markdownテーブル）
├── specialmeetings.pdf   # PDFデータ
├── specialmeetings.docx  # Wordデータ
├── LICENSE.md            # MITライセンス
└── README.md             # このファイル
```

## データへの貢献

新しいイベント事例を追加したい場合は、`specialmeetings.md` の表に行を追加して Pull Request を送ってください。  
追加する際は以下の列を埋めてください。

| 列名 | 記入内容 |
|---|---|
| クラブ名 | クラブ名（国・地域） |
| イベント名 | イベントの正式名称 |
| イベントの概要 | 内容を1〜3文で |
| ページのURL | 参照元URL |
| どんな例会かのタグ | カンマ区切りで複数可 |

## ライセンス

[MIT License](LICENSE.md) © 2026 MASAYUKI TANAKA
