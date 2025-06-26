# order-system-springboot
An order management system built with Spring Boot and PostgreSQL

---

## 📦 概要 / Overview

このシステムは、Spring BootとPostgreSQLを使用して構築された受発注管理アプリケーションです。  
This application is designed to manage B2B order and shipment processes with inventory tracking.

## 🚀 主な機能 / Main Features

- ユーザー認証（JWT認証 & ロール制御） / JWT Authentication & Role-based Access
- 商品登録・編集・削除 / Product management
- 発注・受注・出荷フローの管理 / Order & Shipment flow control
- 在庫管理 / Stock management
- GitHub Actions による CI/CD（予定）/ CI/CD with GitHub Actions (planned)

---

## 🛠️ 使用技術 / Tech Stack

| 項目         | 内容                            |
|--------------|---------------------------------|
| フレームワーク | Spring Boot                     |
| 言語         | Java 17                         |
| データベース | PostgreSQL                      |
| ビルドツール | Gradle                          |
| 認証         | Spring Security + JWT           |
| インフラ     | Docker / GitHub Actions / AWS   |
| テスト       | JUnit / Mockito                 |
| API設計      | Swagger (OpenAPI)               |

---

## 📁 ディレクトリ構成（予定） / Project Structure (planned)
```
order-system-springboot/  
├── src/                  # アプリケーションのソースコードとリソース
│   ├── main/             # メインアプリケーションのソース
│   │   ├── java/         # Javaソースコード
│   │   │   └── com/example/ordersystem/ # パッケージ構造
│   │   └── resources/    # 設定ファイルや静的リソース
│   │       ├── application.yml # Spring Bootなどの設定ファイル
│   │       └── ...       # その他のリソースファイル
│   └── test/             # テストコード
│       ├── java/         # Javaテストコード
│       └── resources/    # テスト用リソース
├── docs/                 # プロジェクトに関するドキュメント
│   └── requirement.md    # 要件定義書など
├── .gitignore            # Gitのバージョン管理から除外するファイルを指定
├── build.gradle          # Mavenプロジェクトの設定ファイル（Gradleの場合は build.gradle）
├── README.md             # このファイル（プロジェクトの概要や使い方）
└── LICENSE               # ライセンス情報
```
---

## 📄 要件定義書 / Requirement Document

👉 [`docs/requirement.md`](./docs/requirement.md)

---

## ✍️ 今後の予定 / Future Plans

- [ ] Swagger によるAPI仕様書生成
- [ ] 発注履歴のCSVエクスポート
- [ ] 管理画面の追加（React or Thymeleaf）
- [ ] 自動デプロイパイプライン（ECS予定）

---

## 📜 ライセンス / License
本プロジェクトは MIT ライセンスのもとで公開されています。
👉 詳細は [LICENSE](./LICENSE) ファイルをご確認ください。
This project is licensed under the MIT License.  
See the [LICENSE](./LICENSE) file for details.
