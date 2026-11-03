# androidprod / droidprod

Scratch、Web（HTML / CSS / JavaScript）、Minecraftに関連するソフトウェアやプロジェクトを開発しています。

オリジナルのミニゲームやWebアプリケーションの制作・公開、開発ツールの開発、ブログでの技術的な制作記録などを行っています。

**Website:** [androidprod / アンドロイドプロット](https://androidprod.f5.si/)

---

## おすすめプロジェクト

### SkinGetBE — Bedrockスキン取得ツール

Minecraft Bedrock Editionの通信スタックを独自実装し、接続してきたクライアントからスキン画像（PNG）を取得・保存する研究目的のツールです。

| バリアント | リポジトリ | 言語 |
|:---:|---|:---:|
| Rust版改良版 | [SkinGetBE-Rust](https://github.com/androidprod/SkinGetBE-Rust) | Rust |
| アプリ版 | [SkinGetBE-APP](https://github.com/androidprod/SkinGetBE-APP) | 要確認 |
| （非推奨）Python移植版 | [SkinGetBEpy](https://github.com/androidprod/SkinGetBEpy) | Python |
| （非推奨）オリジナル版 | [SkinGetBE](https://github.com/androidprod/SkinGetBE) | C++ |

※非推奨のバージョンは、今後アップデートされない場合があります。

---

### TenGun — las2minecraft プロジェクト

LiDARで取得した点群データ（`.las`）をMinecraftのワールドデータに変換するパイプラインです。

| ステップ | リポジトリ | 概要 |
|:---:|---|---|
| 1 | [las2mcfunction](https://github.com/androidprod/las2mcfunction) | `.las` → Minecraftの`setblock`コマンドに変換 |
| 2 | [mcfunction2list](https://github.com/androidprod/mcfunction2list) | mcfunctionから自動化用コマンドリストを生成 |
| 3 | [list2hosting (command2send)](https://github.com/androidprod/list2hosting) | WebSocket経由でBedrock Editionにコマンドを送信 |

---

### Benchmark — ベンチマークソフト

PCの演算性能を計測するベンチマークツールです。

- **通常版:** [Benchmark-Flops](https://github.com/androidprod/Benchmark-Flops)
- **最高性能版:** [Benchmark-Flops-Max](https://github.com/androidprod/Benchmark-Flops-Max)

---

## その他

プロジェクトは随時追加・更新していきます。

---

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/G2G71EPUMU)
