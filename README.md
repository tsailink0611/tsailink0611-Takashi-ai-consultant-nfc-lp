# NFC Landing Page - Takashi Sasaki

AI-Driven Development Consultant の NFC 名刺用ランディングページ

## 🎨 デザインコンセプト

- **Cloudflare Sandbox 風**のミニマルデザイン
- 白黒ベースのモノクロームカラー
- 波線グラフィックアニメーション
- コード風演出でプロフェッショナルな印象

## 🚀 技術スタック

- Pure HTML5
- CSS3 (カスタムプロパティ、アニメーション)
- Vanilla JavaScript
- Vercel (ホスティング)

## 📦 ファイル構成

```
tsailink0611-Takashi-ai-consultant-nfc-lp/
├── index.html          # メインHTMLファイル
├── style.css           # Sandbox風スタイルシート
├── script.js           # vCard保存機能
├── vercel.json         # Vercelデプロイ設定
├── .gitignore          # Git除外設定
└── README.md           # このファイル
```

## ✨ 機能

### 1. vCard 保存機能
連絡先情報を `.vcf` ファイルとしてダウンロード可能

### 2. LINE 連携
LINE公式アカウントへの直接リンク

### 3. レスポンシブデザイン
PC、タブレット、スマートフォンに完全対応

### 4. アニメーション
- 波線グラフィックのアニメーション
- ホバーエフェクト
- スムーススクロール

## 🛠️ ローカル開発

### 1. リポジトリのクローン

```bash
git clone https://github.com/tsailink0611/tsailink0611-Takashi-ai-consultant-nfc-lp.git
cd tsailink0611-Takashi-ai-consultant-nfc-lp
```

### 2. ローカルサーバーの起動

シンプルなHTTPサーバーを起動:

```bash
# Python 3
python -m http.server 8000

# Node.js (http-server)
npx http-server
```

ブラウザで `http://localhost:8000` を開く

## 📤 デプロイ (Vercel)

### 方法1: Vercel CLI

```bash
# Vercel CLIのインストール
npm i -g vercel

# ログイン
vercel login

# デプロイ
vercel --prod
```

### 方法2: GitHub連携 (推奨)

1. GitHubリポジトリをVercelに接続
2. 自動デプロイが設定される
3. `main` ブランチへのプッシュで自動デプロイ

## 🔧 カスタマイズ

### 連絡先情報の変更

`script.js` の `contactInfo` オブジェクトを編集:

```javascript
const contactInfo = {
    firstName: '崇',
    lastName: '佐々木',
    // ... その他の情報
};
```

### デザインの調整

`style.css` のカスタムプロパティを編集:

```css
:root {
    --color-black: #000000;
    --color-white: #ffffff;
    --font-mono: 'IBM Plex Mono', monospace;
    /* ... その他の変数 */
}
```

## 📱 NFC 設定

### iPhone (iOS)
1. 設定 > コントロールセンター > NFCタグリーダーを追加
2. NFCタグにVercelのURLを書き込む

### Android
1. NFC Tools などのアプリをインストール
2. タグにURLを書き込む

## 🌐 本番URL

デプロイ後: `https://tsailink0611-takashi-ai-consultant-nfc-lp.vercel.app`

## 📞 連絡先

- **Name**: 佐々木 崇 (Takashi Sasaki)
- **Email**: tsailink0611@gmail.com
- **LINE**: https://line.me/ti/p/NWGjZAM_AY
- **Location**: 仙台

## 📄 ライセンス

© 2025 Takashi Sasaki. All rights reserved.

---

Built with AI-Driven Development 🤖
