## 🧑‍💻 About Me

Ruby on Rails / Go によるAPI設計、React / Next.js でのUI開発、Terraform を用いた AWS 構築を経験。  
直近では公共案件や20万人規模の AR ゲーム基盤にてAPI開発・管理機能開発・運用改善を推進。
既存システムの構造を理解して、整理・改善できるエンジニアであることを強みとしています。  
横断的に理解しているため、全体最適の視点で改善提案・実装が得意です

---

## 🛠 Tech Stack

| カテゴリ | 技術 |
|---|---|
| Backend | Ruby on Rails |
| Backend | Go |
| Backend | Java / Spring |
| Frontend | React / TypeScript |
| Frontend | Next.js |
| DB | MySQL |
| Infra | Terraform / AWS CDK |
| Infra | AWS (ECS/Fargate, ALB, CloudFront, CodePipeline 等) |
| Other | Protocol Buffers, Sidekiq, SSE, Recoil |

---

## 💼 職務経歴

### Graffity 株式会社

#### [ゴジラAR「ゴジラ VS 東京ドーム」— ゲーム基盤改修・管理画面開発](https://www.at-raku.com/event/tdc-godzilla-ar/)

- 既存の Rails 製マスタ基盤をGoへのリプレイス横展開可能な構造へ刷新
- SSE（Server-Sent Events）を活用したリアルタイム進捗可視化機能を実装
- GameLift 連携によるマッチング結果の管理画面へのリアルタイム通知を実装

---

#### [XR City「ロストアニマルプラネット AR恐竜ゲーム」— スマートフォン向けゲームアプリ開発](https://www.nttqonoq.com/)

NTT QONOQ 受託案件。総ユーザー数20万人超え、2年2ヶ月の設計・開発・運用を担当。

- Protocol Buffersを採用して、Unity(C#) と Ruby のスキーマ互換性を維持
- Push 通知基盤を設計・実装。Sidekiq による非同期化 + 500件単位の子ジョブ分割 + スロットリングによる防御的設計
- インゲーム / アウトゲーム API 群の開発（デッキ編成、育成、ショップ/課金、PvE/PvP、ランキング、スキル等）

---

### 個人事業主

#### [ARナビゲーション Web アプリ「タカノメAR」](https://www.softbankhawks.co.jp/news/detail/202300227236.html)

- GPS・方位データを用いた **AR ナビゲーション UI** の実装
- 緯度経度からの距離計算ロジック、カメラ映像へのオーバーレイ UI を設計・実装

---

#### 水道局向け管理システム

- PDF ビューワー機能（ズーム / パン / ドラッグ）の設計・実装
- 座標変換ロジックを用いた **矩形アノテーション機能** の開発
- OCR 解析結果と PDF 位置情報の紐付け機能を実装
- Recoilによる複雑な UI 状態管理設計

---

#### ライブ配信アプリ KPI 分析基盤構築

- MAU・WAU・DAU 等の KPI ダッシュボード設計
- API 経由データの集計 SQL クエリ設計・最適化、**Redash** での可視化・定期レポート自動化
- **技術スタック:** MySQL / Redash

---

#### [ALT 教員向けクラウドサービス](https://www.interac.co.jp/teachers_cloud/)

15,000点以上のコンテンツを提供する教育プラットフォーム。モック作成から設計・実装まで一貫担当。

- 学年ごとに要件が異なる教材フォルダの **階層構造設計**・ネスト対応の再帰処理実装
- CSV アップロード機能、年度末一括パスワード更新機能の実装
- **AWS CodePipeline × ECS Fargate** への自動デプロイ環境を構築
- **技術スタック:** Ruby on Rails / MySQL / AWS

---

#### [物件サイト改修（りのべる）](https://www.renoveru.jp/lp-event-sr-gp01?utm_source=google&utm_medium=cpc&utm_campaign=tyo_g_lis_br_bra_textrsa_no_many_jp-no-r-lpeventsrgp01_lptest2601&gad_source=1&gad_campaignid=23688990374&gbraid=0AAAAADmeq-nOK44orfle8fO1HCKn9XpM4&gclid=CjwKCAjwhLPOBhBiEiwA8_wJHAfZv6ynt4lSUNLSWIPj6gQF319_RWM8mhhurqUAW7BiWZdhYaRc2hoCT2wQAvD_BwE)
*2020年5月 〜 2023年5月*

- Rails 5 → Rails 6 アップデート対応
- CMS 管理画面の機能追加・改修
- クエリ最適化・N+1 解消によるパフォーマンス改善

---

#### ミエルカコネクト — サービス開発

- マーケターと企業をつなぐマッチングサービスのフロントエンド設計〜実装
- API 連携・状態管理設計、UI 改善・パフォーマンス最適化

---

### 株式会社インフラトップ

> DMMグループ・社会人向け IT 教育事業「DMM WEBCAMP」の運営会社。

- **プログラミングメンター**（HTML / CSS / JavaScript / Ruby on Rails / AWS）
- エンジニア開発組織の立ち上げ（Git 運用ルール策定・コードレビュー体制構築）
- 社内CRM システム開発（要件定義〜設計〜実装〜運用）
- カレンダー予約システム開発・CRM データ連携
- HubSpot導入・カスタマイズによるマーケティング施策の自動化
- MDM 導入による社内端末管理体制の構築

---

### TDCソフト株式会社

- 給湯器メーカー法改正対応システムの総合テスト設計（テストケース約 1,000件）
- 塾向け管理システム再開発：生徒情報変更履歴機能の詳細設計・テーブル設計
- 配送システム新規開発：管理画面 CRUD 機能・見積書 PDF 発行機能の設計〜実装

---

## 📬 Contact

お仕事のご相談・ご連絡はこちらからお気軽にどうぞ。

https://x.com/blastoise_1009

---

*Last updated: 2026年2月*
