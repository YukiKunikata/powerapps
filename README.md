# 日報アプリ（Power Apps）

## 概要
一覧・新規登録・編集が可能なレスポンシブ対応アプリ

## 主な機能
- 一覧表示
- 新規登録
- 編集
- モバイル対応（1画面切替）

## 技術
- Power Apps (Canvas)
- Container Layout
- Responsive Design

## インポート方法
Power Apps の「パッケージのインポート」機能で読み込み可能

## 承認フロー（Power Automate）
このアプリでは、Power Automateを利用した承認フローを実装しています。

### 処理概要
1. ユーザーが日報を登録
2. 承認フローが自動起動
3. 上長に承認依頼を送信
4. 承認 / 却下結果をアプリに反映

### 使用技術
- Power Automate
- 承認アクション
- 条件分岐
