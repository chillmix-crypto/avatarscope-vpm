# VPM Repository Hosting (chillsan 用メモ)

## このフォルダの内容
- index.json                                  ← VPM Listing
- com.chill.avatarscope-0.9.0.zip    ← パッケージ本体 ZIP

## GitHub Pages へのデプロイ手順 (初回のみ)
1. GitHub で新しいリポジトリを作成（例: avatarscope-vpm）
2. 設定で Pages を有効化 (Settings → Pages → Source: main / root)
3. このフォルダの中身全部をリポジトリのルートに push

## アップデート時
1. AvatarScope のバージョンを上げて Build Distribution を実行
2. 新しい index.json と zip を Pages リポジトリに push (古い zip は残してOK)
3. VCC ユーザーは「Refresh」ボタンで新バージョンを取得できる

## 購入者に伝える URL
https://chillmix-crypto.github.io/avatarscope-vpm/index.json

VCC の Settings → Packages → Add Repository でこの URL を貼ると
パッケージ一覧に AvatarScope が出現する。
