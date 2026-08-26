# needs-golf-lp

プライベートジムNeeDS（株式会社NeeDS）の、40〜60代ゴルファー向け集客ランディングページ。

## ファイル

| パス | 内容 |
|---|---|
| `index.html` | LP本体。CSS・JSを内包した単体HTML。外部依存はGoogle FontsとGTMのみ |
| `images/hero.jpg` | ファーストビューの写真 |

## コンセプト

「動きが変われば、スイングが変わる。」
胸椎の回旋・股関節・肩甲骨の動きを作り直すことで、フォーム矯正ではなく「動きからスイングを作る」アプローチを訴求する。

- ターゲット：40〜60代の男性ゴルファー
- 集客：広告出稿が中心
- CTA：公式LINE登録 → 無料体験予約（ページ内6箇所＋モバイル固定バー）
- ブランドカラー：`#0d669b`
- 計測：Google Tag Manager `GTM-P95C26ZR`。CTAクリック時に `cta_click` イベントを送信（`cta_position` で設置場所を識別）

## 公開先

- 確認用：GitHub Pages
- 本番（予定）：ロリポップ上の `golf.nds-training.jp`

## 公開前の残作業

- [ ] ロゴ画像（ヘッダー＝白背景用／フッター＝紺背景用の2種）
- [ ] 写真（`[PHOTO: ...]` ラベル付きのプレースホルダー箇所すべて）
- [ ] トレーナー氏名・お客様氏名
- [ ] LINE誘導リンク（現在は `#line-cta` の仮置き）
- [ ] SNSリンク（Instagram / Facebook / YouTube）
- [ ] `<meta name="robots" content="noindex,nofollow">` の削除
- [ ] 無料体験セクションの通常価格（見せ消し表示を使う場合）
