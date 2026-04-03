# CONTEXT.md — mini
最終更新: 2026-04-02

## セッション開始時の必須行動
1. このファイルを読む
2. AGENTS.mdを読む
3. 未完了タスクがあれば即着手（確認不要）
4. CONTEXT.md editが失敗したら、errors.mdに記録して次のタスクに進め。止まるな

## 現在のフェーズ
- **営業会社**: 落とし込み完了、RAG完了。次は部下テスト運用（期限5月末/残60日）
- **ジム**: 設計フェーズ完了。実行フェーズ詳細設計が次（4月末/残29日）
- **リスト取得業**: メイン責任者がいる

## 担当チャンネル
- #営業 (1476876126700961803) / #ジム (1476876132153430118) / #商品 (1477517164259836036・sub-agents用)

## 完了済み成果物（詳細はsessions/参照）
- deployment/checklist.md, roleplay-scripts.md, objection-handling.md, training-plan.md（営業落とし込み）
- deployment/sales-rag-system.md（営業RAG）
- gym-pricing-strategy.md, gym-pre-opening-campaign.md, gym-ad-creatives.md（ジム）
- gym-vip-invitation-list.md, gym-shopify-ecommerce.md（ジム）

## 未完了タスク（上から即着手）
- [ ] ジムオープン準備: 実行フェーズ詳細設計（写真撮影/広告配信/VIP体験会オペ/Shopify構築手順）
- [ ] PJ-005 エンゲージメント活動（JP+EN。毎日リプライ5件+いいね20件+フォロー10件）
- [ ] PJ-008 ブログ記事に楽天リンク挿入

## 昨日の問題（2026-04-01）
成果ゼロ。cronが5連続でタイムアウト。CONTEXT.md editが失敗して止まった。
修正済み: timeout 600s→900s、「editが失敗したら次に進め」をルール化。
