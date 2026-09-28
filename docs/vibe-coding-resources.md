# バイブコーディング・リソース集

UI制作やデザイン改善のときに参照する厳選リソース（29個）。用途別にグループ化している。

> **このリポジトリでの使い方の前提**
> `index.html` はビルド工程のない素のHTML/CSS/JSアプリ。React/Tailwind前提のリソースは
> 「デザインの参考」または「HTML/CSSへ書き換えて移植」として使う。そのまま使えるものには ✅ を付けている。

## 1. デザインの方向性・インスピレーション（エージェントに渡す参考素材）

| # | リソース | URL | 中身・使いどころ |
|---|---|---|---|
| 1 | scrolltide | https://scrolltide.co | 3D・スクロール駆動サイト向けの200以上のフルビルドプロンプト。部品単位ではなく完全なデザインブリーフ |
| 2 | Minimal Gallery | https://minimal.gallery | エージェントに見せる高品質サイトのキュレーション |
| 3 | Kage | https://kage.design | 実在UIのインスピレーションをプロンプトに直接マッピング |
| 4 | Refero Styles | https://styles.refero.design | タイポグラフィ込みの実製品スタイル2,000以上 |
| 11 | DESIGNmd | https://designmd.ai | エージェントが読めるMarkdown形式のデザインシステム |
| 12 | VibePrompt | https://vibeprompts.dev | ダッシュボード・LP向けの既製プロンプト |

## 2. UIパターン別ギャラリー（特定パーツの参考）

| # | リソース | URL | 中身・使いどころ |
|---|---|---|---|
| 5 | Component Gallery | https://component.gallery | 同じUI要素をトップのデザインシステムがどう解くか、2,600以上の実例 |
| 6 | AppShot Gallery | https://appshot.gallery | モバイル向け実アプリのスクリーンショット |
| 7 | Navbar Gallery | https://navbar.gallery | ナビゲーションバー |
| 8 | Footer Design | https://footer.design | フッター |
| 9 | CTA Gallery | https://cta.gallery | コンバージョン検証済みのフォーム・ポップアップ・ボタン |
| 10 | 404s | https://404s.design | 404ページ |

## 3. コンポーネントライブラリ（React / Tailwind 中心）

| # | リソース | URL | 中身・使いどころ |
|---|---|---|---|
| 13 | 21st.dev | https://21st.dev | MCP経由でエージェントに直接つなげるコンポーネントレジストリ |
| 15 | shadcn/ui | https://ui.shadcn.com | 定番のゴールドスタンダード |
| 16 | Aceternity UI | https://ui.aceternity.com | アニメーション付きReact/Tailwindコンポーネント200以上 |
| 17 | Magic UI | https://magicui.design | アニメーション付きコンポーネント |
| 18 | Motion Primitives | https://motion-primitives.com | モーション系のプリミティブ |
| 19 | Uiverse ✅ | https://uiverse.io | コミュニティ製UI部品。素のHTML/CSS版があるので本リポジトリにそのまま使える |
| 20 | UIAble | https://uiable.com | UIコンポーネント集 |
| 21 | mapcn | https://mapcn.dev | 地図コンポーネント（マーカー・ルート・ポップアップ）。物件所在地の表示に応用可 |

## 4. モーション・マイクロインタラクション・エフェクト

| # | リソース | URL | 中身・使いどころ |
|---|---|---|---|
| 14 | Kinetics | https://kinetics.colorion.co | Reactコード＋プロンプト付きのモーションエフェクト150以上 |
| 22 | MicroKit UI | https://microkit.co | マイクロインタラクション |
| 23 | Liquid Glass | https://glass.samasante.com | ガラス屈折（Liquid Glass）コンポーネント |
| 24 | CSS Text Effects ✅ | https://text-effects.colorion.co | CSSだけのテキストエフェクト |
| 25 | Circle Loaders ✅ | https://circleloaders.dominikakissi.com | 円形ローダー。AI解析中の待機表示に |
| 26 | Gradient Buttons ✅ | https://gradientbuttons.colorion.co | グラデーションボタン |
| 29 | Anime.js ✅ | https://animejs.com | 軽量JSアニメーションライブラリ。CDN（cdnjs / jsdelivr）読み込みで素のJSから使える |

## 5. イラスト・アイコン素材

| # | リソース | URL | 中身・使いどころ |
|---|---|---|---|
| 27 | Kitbitz | https://kitbitz.art | 手描きイラスト2,000以上 |
| 28 | 3Dicons | https://3dicons.co | 3Dアイコン |

## 目的別クイックガイド

- **全体の見た目を刷新したい** → 1 scrolltide / 3 Kage / 4 Refero Styles で方向性を決め、11 DESIGNmd 形式で書き起こす
- **特定パーツを良くしたい** → 5 Component Gallery で実例を確認 → 7〜10 の専用ギャラリー
- **アップロード欄・結果カードを動かしたい** → 25 Circle Loaders / 29 Anime.js / 22 MicroKit UI
- **CTA・フォームを改善したい** → 9 CTA Gallery / 26 Gradient Buttons
- **物件の地図表示を足したい** → 21 mapcn（React前提なので、素のJSならLeaflet等への置き換えも検討）
- **挿絵・アイコンが欲しい** → 27 Kitbitz / 28 3Dicons（ライセンスは各サイトで確認）

## 注意

- 外部素材を取り込むときは各サイトのライセンスを確認すること。
- ブランドカラー（`--navy:#0B2545` / `--gold:#C8922A`）とフォント（Zen Kaku Gothic New / Outfit）に合わせて調整すること。
