# ORIHIRASHO Official Website

織平翔 / Sho Orihira の公式サイト用スターターです。  
HTML / CSS / JavaScript だけで動くので、無料ホスティングにそのまま置けます。

## ファイル構成

```txt
orihirasho-site/
├── index.html
├── styles.css
├── script.js
└── assets/
    ├── logo.svg
    ├── cover-mirror.svg
    ├── og-image.svg
    └── favicon.svg
```

## 編集する場所

### 1. 配信リンク

`index.html` の `Latest Release` セクションにある `href="#"` を実際のURLに変えてください。

```html
<a href="ここにSpotifyのURL">Spotify</a>
<a href="ここにApple MusicのURL">Apple Music</a>
```

### 2. SNSリンク

`index.html` の `Connect` セクションにある `X`, `Instagram`, `NicoNico`, `Streaming` の `href="#"` を差し替えてください。

### 3. プロフィール文

`Profile` セクションの文章を、正式なプロフィール文に差し替えてください。

### 4. ジャケット画像

`assets/cover-mirror.svg` を本物のジャケット画像に差し替える場合は、画像名を `cover-mirror.jpg` などにして、`index.html` 側も変更してください。

## 無料公開方法：Netlifyが一番ラク

1. `orihirasho-site` フォルダをzipから展開
2. Netlifyにログイン
3. 「Add new site」→「Deploy manually」
4. フォルダをドラッグ＆ドロップ
5. 公開URLが発行されます

## GitHub Pagesで公開する場合

1. GitHubで `orihirasho-site` というリポジトリを作成
2. この中身をアップロード
3. Settings → Pages
4. Source を `Deploy from a branch`
5. Branch を `main` / `/root` にして保存
6. `https://ユーザー名.github.io/orihirasho-site/` で公開

## Vercelで公開する場合

1. GitHubにアップロード
2. VercelでImport
3. Framework PresetはOther
4. Build Commandは空欄
5. Output Directoryも空欄
6. Deploy
