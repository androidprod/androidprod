# 👾 androidprod / droidprod

Scratch・Web（HTML/CSS/JavaScript）・Minecraftに関連するプロジェクトを制作しています。  
オリジナルのミニゲームやWebアプリの公開、ブログでの制作記録なども行っています。

🌐 **サイト:** [aprd's site](https://androidprod.f5.si/)

---

## 🌟 おすすめプロジェクト

---

### 🎭 SkinGetBE — Bedrockスキン取得ツール

Minecraft Bedrock Editionの通信スタックを独自実装し、  
接続してきたクライアントからスキン画像（PNG）を自動取得・保存する研究目的のツールです。

| バリアント | リポジトリ | 言語 |
|:---:|---|:---:|
| オリジナル版 | [SkinGetBE](https://github.com/androidprod/SkinGetBE) | C++ |
| Python移植版 | [SkinGetBEpy](https://github.com/androidprod/SkinGetBEpy) | Python |

---

### 🗺️ TenGun — las2minecraft プロジェクト

LiDAR点群データ（`.las`）をMinecraftのワールドデータに変換するパイプラインです。

| ステップ | リポジトリ | 概要 |
|:---:|---|---|
| 1️⃣ | [las2mcfunction](https://github.com/androidprod/las2mcfunction) | `.las` → Minecraft `setblock` コマンドに変換 |
| 2️⃣ | [mcfunction2list](https://github.com/androidprod/mcfunction2list) | mcfunctionから自動化用コマンドリストを生成 |
| 3️⃣ | [list2hosting (command2send)](https://github.com/androidprod/list2hosting) | WebSocket経由でBedrock Editionにコマンドを送信 |

---

### ⚡ Benchmark ソフト

PCの演算性能を計測するベンチマークツールです。

- 🟢 **通常版:** [Benchmark-Flops](https://github.com/androidprod/Benchmark-Flops)
- 🔴 **最高性能版:** [Benchmark-Flops-Max](https://github.com/androidprod/Benchmark-Flops-Max)

---

> 📌 プロジェクトは随時追加していきます！
