# 自己紹介・ポートフォリオサイト

HTML / CSS / JavaScript のみで作った、スマホ対応のポートフォリオサイトです。インストール・ビルド不要。GitHub Pages で無料公開できます。

## 1. 内容を変更する

VS Code で `index.html` を開き、次の場所を修正してください。

- `<title>あなたの名前 | Portfolio</title>` : ブラウザのタイトル
- `こんにちは、<strong>あなたの名前</strong>です。` : 表示名
- About（私について）の本文 : 自己紹介
- Projects（制作実績） : 公開してよい範囲でプロジェクト内容を修正
- Skills（スキル） : 使用できる言語とツール
- フッターの `あなたの名前` : 表示名

**注意**：ページの制作実績はこれまでの活動をもとにした文章案です。公開前に、実際の活動と一致しているか確認してください。学校名、本名、住所、電話番号、メールアドレス、API キー、認証情報などの個人・機密情報を公開しないでください。

見た目の色は `style.css` の先頭の `:root` 内で変更できます。ページの動作は `script.js` です。

## 2. PCで確認

`index.html` をダブルクリックしてブラウザで開きます。PC・スマホの画面幅（ブラウザのデベロッパーツール）で確認してください。

## 3. GitHub Pages にアップロードして無料公開

1. https://github.com/ でログイン。
2. `New repository` から新しいリポジトリを作成（例：`my-portfolio`）。GitHub Free の場合は `Public` にします。
3. リポジトリの `Add file` → `Upload files` で以下をアップロードします（ZIP は解凍してから、中のファイルをアップロード）。
   - `index.html`
   - `style.css`
   - `script.js`
   - `assets/favicon.svg`（フォルダごと）
   - `README.md`（任意）
4. `Commit changes` をクリック。
5. リポジトリの `Settings` → `Pages` を開く。
6. `Build and deployment` の `Source` を `Deploy from a branch` にする。
7. `Branch` を `main`、フォルダを `/(root)` に設定し、`Save` をクリック。
8. 表示された `Visit site` または `https://<ユーザー名>.github.io/my-portfolio/` にアクセス。反映に数分かかる場合があります。

**ポイント**： `index.html` がリポジトリの一番上の階層にあることを確認してください。`my-portfolio/index.html` のように余分なフォルダを挟むと、Root 指定ではページが見つかりません。

公式ガイド：https://docs.github.com/ja/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 4. 更新

ローカルでファイルを編集し、GitHub で該当ファイルを更新して `Commit changes` すると公開サイトにも反映されます。

## ファイル構成

```
my-portfolio/
├── index.html       # 内容とページの構造
├── style.css        # デザイン・レスポンシブ設定
├── script.js        # ダークモード・スマホメニュー
├── assets/
│   └── favicon.svg  # タブに表示するアイコン
└── README.md        # この手順書
```
