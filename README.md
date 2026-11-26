# testing-app-practice

## 概要
COACHTECH 教材 Tutorial 10-5「テスト ハンズオン演習」で作成した成果物です。
Laravelのテスト機能を使って、ユーザー作成機能のテストコードを作成しました。

## 使用技術
- PHP 8.x
- Laravel 10.x
- PHPUnit（テスト）
- Eloquent / Factory
- Laravel Sail（Docker Compose）

## 学んだこと
- Feature テストと Unit テストの違いと使い分け（今回はFeature テスト）
- RefreshDatabase トレイトを使ったテスト用 DB のリセット
- assertDatabaseHas() や expectException() を使ったアサーションの書き方

## 動作確認
- http://localhost
  - LaravelのWelcomeページが表示されることを確認

- sail artisan test --filter UserTest を実行