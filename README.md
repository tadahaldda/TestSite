# GTA RPサーバー公式風ホームページ テンプレート

## ファイル構成

```text
gta-server-site/
├─ index.html
├─ style.css
├─ README.md
└─ images/
```

## 使い方

1. `index.html` をブラウザで開く
2. サーバー名、Discordリンク、説明文を自分のサーバー用に変更する
3. 画像を使う場合は `images` フォルダに画像を入れる
4. `style.css` の `.hero` 内にある画像URLを `url("images/hero.jpg")` などに変更する

## 主な差し替え場所

| 変更内容 | ファイル | 探す文字 |
|---|---|---|
| サーバー名 | index.html | NOVA CITY RP |
| Discordリンク | index.html | https://discord.gg/xxxxx |
| トップ画像 | style.css | images/hero.jpg または Unsplash URL |
| お知らせ | index.html | section id="news" |
| ルール | index.html | section id="rules" |
| 職業紹介 | index.html | section id="jobs" |

## 注意

- GTA公式画像やロゴの無断使用は避けてください。
- 公開サイトでは、自作画像、許可済み画像、フリー素材の使用がおすすめです。
