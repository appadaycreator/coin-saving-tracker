# 小銭貯金・貯金箱記録ツール【無料】記録・管理アプリ - 技術仕様書

## 概要

**サービス名**: Coin Saving Tracker
**バージョン**: 1.0.0
**更新日**: 2026-05-27
**URL**: https://appadaycreator.com/coin-saving-tracker/

小銭貯金の総額をリアルタイム計算。100円・500円貯金など目標設定も対応。登録不要・完全無料でご利用いただけます。

## データ管理

- **ストレージ**: ブラウザ localStorage（外部API通信なし）
- **永続化**: ページ読み込み時に自動復元
- **クリア**: ブラウザのサイトデータ削除で初期化

## 技術スタック

- HTML5 / CSS3 / Vanilla JavaScript
- PWA対応（manifest.json / Service Worker）
- レスポンシブデザイン（モバイルファースト）

## 使い方

1. ページを開き、入力フォームの項目を確認する
2. 必要な情報を入力または選択する
3. 実行ボタンをクリックして結果を取得する
4. 表示された結果・アドバイスを確認する
5. 必要に応じてコピー・SNSシェアで活用する

## よくある質問（FAQ）

**Q: 小銭貯金・貯金箱記録ツールは無料で使えますか？**

はい、完全無料・登録不要でご利用いただけます。

**Q: 何回でも使えますか？**

はい、回数制限なく何度でもご利用いただけます。

**Q: 入力したデータはサーバーに送信されますか？**

いいえ。すべての処理はブラウザ内で完結し、入力内容はサーバーへ送信されません。

**Q: スマートフォンでも使えますか？**

はい、スマートフォン・タブレット・PCすべてに最適化されています。

**Q: 結果を保存・共有できますか？**

スクリーンショットでの保存またはSNSシェアボタンからご共有いただけます。


## 関連サービス

- [Household Budget Analyzer](https://appadaycreator.github.io/household-budget-analyzer/)
- [🔥 FIRE計算機](https://appadaycreator.github.io/fire-calculator/)
- [💰 サブスク断捨離計算機](https://appadaycreator.github.io/subscription-calculator/)

## テスト

| ファイル | フレームワーク | 概要 |
|---------|--------------|------|
| `tests/e2e/` | Playwright | 本番URL対象E2E（Jest対象外） |

## デプロイ

GitHub Pages（mainブランチ push → 自動デプロイ）

## ライセンス

MIT License
