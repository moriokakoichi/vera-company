# VERA会社案内 v4（統合確定版）｜ 公開・差し替え手順（GitHub Pages）

このフォルダ（`_publish`）が、そのまま公開できる「完成一式」です。入口は `index.html`。

## いまの公開状態（2026-06-27 時点・確認済み）
- 公開先＝**GitHub Pages**（Netlifyはクレジット上限で停止したため移行）
- リポジトリ＝**moriokakoichi/vera-company**
- 本番URL＝**https://moriokakoichi.github.io/vera-company/** （表示・内容ともライブ確認済み）
- 公開ファイル＝5つ（`index.html` ／ `sign_morio_white.png` ／ ロゴSVG3つ）

## 差し替えたいとき（中身を直したら）
1. **https://github.com/moriokakoichi/vera-company** を開く（GitHubにログイン）
2. 直したファイルを開く → 右上の鉛筆✏️で編集、または **「Add file → Upload files」** で上書きアップロード
3. 下の **「Commit changes」** を押す
4. **1〜2分で自動反映**（URLは変わらない）。反映しないときはブラウザを更新（Ctrl+F5）
   - 画像やロゴも変えた場合は、その5ファイルをまとめて上げ直すのが確実

## はじめて公開し直す場合（リポジトリを作り直すとき）
1. GitHubで **New repository** → 名前 `vera-company`（Public）
2. **Add file → Upload files** で、この `_publish` の中身 **5ファイルをドラッグ**（`index.html` が最上層に来るように）→ Commit
3. **Settings → Pages** → Source=「Deploy from a branch」/ Branch=`main`・`/ (root)` → Save
4. 数分後 **https://（ユーザー名）.github.io/vera-company/** で公開

## もっと簡単に済ませたい場合（予備・一時URL）
- 親フォルダの `VERA会社案内_v4_公開用.zip` を **https://tiiny.host** にドラッグするだけでも即URLが出ます（無料／軽い広告表示あり）。一時的な共有向け。

## 中身（参照しているファイル）
- `index.html` … 会社案内本体（入口）
- `vera_logo_2color.svg` … 表紙の2色ロゴ（赤×紺）
- `vera_logo_mono_navy.svg` … CONCEPTの紺シンボル
- `vera_logo_white.svg` … フッターの白抜きロゴ
- `sign_morio_white.png` … 代表メッセージの直筆サイン（白・背景透過）

## 独自ドメイン（将来）
- 正式ドメイン＝**vera-holdings.co.jp**（.co.jp は登記済み法人専用＝**設立7/9以降**に取得可能）。
- 接続手順＝親フォルダ `独自ドメイン接続手順_co.jp_7月9日以降.md`（DNS値はGitHub Pages公式・確認済み）。
- 7/9前に独自ドメインを使いたい場合は **.com／.jp** なら今すぐ取得・接続可能（同じDNS手順）。

## 注意
- `noindex` 設定済み（検索に出ません＝商談相手・身内に見せる用）。機密は載せていません。
- VERAハウス（VERA House）の商標は出願準備中。®や「登録商標」は付けないこと。
- 印刷/PDF配布は、親フォルダの `VERA会社案内_v4.pdf`（A4・全10ページ）を使用。
