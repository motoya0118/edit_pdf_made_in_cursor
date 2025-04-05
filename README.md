# PDF Editor

ブラウザ上で動作するシンプルなPDFエディターです。PDFのページ操作（複製、削除、結合）をフロントエンドで完結させることができます。

## 機能

- PDFのページ複製
- PDFのページ削除
- 複数のPDFの結合
- PDFのダウンロード

## 技術スタック

- HTML5
- CSS3
- JavaScript
- [PDF.js](https://mozilla.github.io/pdf.js/) - PDFの表示と操作
- [PDF-Lib](https://pdf-lib.js.org/) - PDFの編集

## セットアップ

1. リポジトリをクローン
```bash
git clone [repository-url]
cd pdf-editor
```

2. 必要なパッケージをインストール
```bash
npm install
```

3. ローカルサーバーを起動
```bash
npx http-server
```

4. ブラウザでアクセス
```
http://localhost:8080
```

## 使い方

1. PDFをアップロード
   - 「PDFをアップロード」セクションからPDFファイルを選択

2. ページの選択
   - プレビュー表示されたページをクリックして選択
   - 複数のページを選択可能

3. ページの操作
   - 「選択ページを複製」: 選択したページを複製
   - 「選択ページを削除」: 選択したページを削除
   - 「選択を解除」: すべての選択を解除

4. PDFの結合
   - 「PDFを結合」ボタンをクリック
   - 結合したいPDFファイルを選択

5. 編集したPDFのダウンロード
   - 「PDFをダウンロード」ボタンをクリック

## 特徴

- すべての処理がブラウザ上で完結
- サーバーサイドの処理が不要
- 直感的なユーザーインターフェース
- リアルタイムプレビュー
- 処理中のローディング表示

## 注意事項

- 大きなPDFファイルの処理には時間がかかる場合があります
- ブラウザのメモリ制限により、非常に大きなPDFの処理ができない場合があります
- 対応ブラウザ: Chrome, Firefox, Safari, Edge の最新版

## ライセンス

MIT License 