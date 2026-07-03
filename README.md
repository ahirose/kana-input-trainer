# かな入力トレーナー (Kana Input Trainer)

For learners of Japanese Kana input method with JIS keyboard.

JIS配列キーボードで、刻印されたかなを**直接打つ**練習用のブラウザツールです。ローマ字入力ではなく、かな入力モード（英数OFF）での打鍵を身につけたい方向けです。

**ライブデモ:** https://ahirose.github.io/kana-input-trainer/

## 特徴

- **JIS配列のビジュアルキーボード** — 次に押すキーをハイライト表示
- **段階的なレッスン** — あ行 → か行・さ行 → 濁音・半濁音 → 小書き・拗音 → 単語・カタカナ → 短文
- **リアルタイム統計** — 打鍵/分、正確率、進捗、ミス数
- **指の色・かな表示の切り替え** — キーボード下のチェックボックスで調整
- **インストール不要** — 単一の HTML ファイル。オフラインでも利用可能

## 使い方

1. レッスンを選ぶ（あ行から順に進めるのがおすすめ）
2. 画面上のかなを、物理キーボードで入力する
3. 濁点は `゛` キー、半濁点は `゜` キー、小さいかなは `Shift` を使う

### 推奨環境

- **JIS配列**の物理キーボード
- かな入力モード（または英数OFF）に切り替えた状態での練習

## GitHub Pages で公開する

1. このリポジトリを GitHub にプッシュする
2. リポジトリの **Settings → Pages**
3. **Build and deployment → Source** で **Deploy from a branch** を選択
4. **Branch** を `main`、フォルダを `/ (root)` に設定して **Save**
5. 数分後、`https://<username>.github.io/kana-input-trainer/` で公開されます

## ローカルで開く

`index.html` をブラウザで開くだけで動作します。

```bash
# 例: Python で簡易サーバーを立てる場合
python -m http.server 8000
# http://localhost:8000 を開く
```

## ライセンス

MIT（必要に応じて変更してください）
