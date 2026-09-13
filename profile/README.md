# Start-X / スタートエックス

We are building the operating system for marketing decisions.
私たちは、マーケティングの意思決定のための OS を作っている。

- 🌐 商用プロダクト / Commercial: **[marketing-os.jp](https://marketing-os.jp)** — The decision OS for marketing teams
- 📜 思想 / Philosophy & boundary: **[manifesto](https://github.com/start-x-work/manifesto)**

---

## オープンソース / Open Source (`mos-*`)

すべて **BYOK（自分のAPIキー）・ローカル完結・下書き優先（最終判断は人）** で動きます。**生成（判断）は人、組立は機械** が共通の設計思想です。

### すぐ使える（npm 公開済み）/ Ready to use — published on npm

| Repo | 内容 / What | Install |
|---|---|---|
| 🔍 [marketing-os-seo](https://github.com/start-x-work/marketing-os-seo) | LLMO/AEO 時代の SEO ツールキット（診断・評価・編集可能な成果物） | `npx @start-x-work/mos-seo` |
| 📊 [marketing-os-ads](https://github.com/start-x-work/marketing-os-ads) | 広告コピー・運用の支援 | `npx @start-x-work/mos-ads` |
| 💬 [marketing-os-social](https://github.com/start-x-work/marketing-os-social) | SNS 運用の支援 | `npx @start-x-work/mos-social` |
| 🧰 [mos-kit](https://github.com/start-x-work/mos-kit) | 上記が共有する共通基盤ライブラリ | `@start-x-work/mos-kit` |
| 🎨 [mos-creative](https://github.com/start-x-work/mos-creative) | クリエイティブ制作支援（ブリーフ→生成→表現ガード→人の承認証跡）。ローカルファースト・下書き優先（v0.1） | `@start-x-work/mos-creative` |

### 新規公開 / Newly released

| Repo | 内容 / What | 使い方 |
|---|---|---|
| 🎬 [mos-video](https://github.com/start-x-work/mos-video) | **手渡し0円パイプライン**。企画・台本・画像は人が手渡し、検証・音声・字幕・演出・全SNSサイズ書き出し・納品をローカルで自動処理。**自動投稿はしない**（Python / v1.0） | `pip install -e .`（[README](https://github.com/start-x-work/mos-video)） |

> 補足: SEO / Ads / Social / creative と共通基盤 kit は npm から今すぐ使えます。以前の README にあった「Coming 2027」は公開済みに更新しました。

---

## 共通の約束 / What these tools do (and don't)

- ✅ **する**: ローカルでの診断・下書き生成・表現の気づき・編集可能な成果物・人の承認
- ❌ **しない**: SNS等への自動投稿・無人承認・APIキーやデータの外部送信・成果の保証

---

## 開発に参加する / Contributing

各リポジトリは **Git Flow（`main` / `develop`）** で運用しています。変更は PR 経由で、CI を通してからマージします。詳細は各リポの `CONTRIBUTING.md` / `CLAUDE.md`（人間・AIエージェント共通の行動規範）を参照してください。

---

## Philosophy / 思想

Marketing is, at its core, an act of editing.
We build the tools that scale that act beyond any single editor.

マーケティングの本質は「編集」である。
私たちは、ひとりの編集者を超えて編集行為を拡張する道具を作る。

詳細は [manifesto](https://github.com/start-x-work/manifesto) を参照 / Read our [manifesto](https://github.com/start-x-work/manifesto).
