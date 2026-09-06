# Final Validation — ≠ME「愛くださいませ」

- 実施日: 2026-09-05
- 判定: **PASS WITH DOCUMENTED LIMITATIONS**
- 対象: 全Phase成果物、Evidence Report、Claim-Evidence Table、References / Source Inventory、Public Report、research_status、Google Drive配置

## 1. 必須成果物

| 成果物 | 状態 | 検証 |
|---|---|---|
| Evidence Report | 完成 | Driveアップロード・再読込済み |
| Claim-Evidence Table（MD） | 完成 | 43 Claim、連番・重複なし、再読込済み |
| Claim-Evidence Table（CSV） | 完成 | MDと43 ID完全一致、CSV parse成功 |
| References / Source Inventory | 完成 | S01–S51、D01–D05、C01–C05を定義 |
| Public Report（note想定） | 完成 | 約4,500字、独立した批評記事、再読込済み |
| Phase 8 Evidence Audit | 完成 | 限定付きPass、修正ログあり |
| research_status | 更新中 | 本Validation保存後にPhase 0–10完了へ更新 |

## 2. Evidence Report ↔ Public Report整合

| 検証軸 | Evidence Report | Public Report | 結果 |
|---|---|---|---|
| 公開順 | 05-16初披露、06-09配信、06-24発売 | 同一 | Pass |
| 人数／センター | 11名、公式はセンター概念なし | 11人、固定センターを置かない | Pass |
| 制作 | 作詞・作曲・編曲・演奏者 | 齋藤奏太、APAZZI、演奏編成を一致記載 | Pass |
| クラシック参照 | デモ段階の《幻想即興曲》オマージュ | 同一。APAZZI発信へリンク | Pass |
| MV配役 | 4人の堕天使＋7体の人形 | 同一 | Pass |
| MV時代 | 1999年7月の日本 | 同一 | Pass |
| 振付 | 公式「最高難度」、akaneの繊細さ／呪い | 公式評価として同一 | Pass |
| Billboard Sales | 431,769枚、1位 | 同一 | Pass |
| Oricon | 31.0万枚、1位 | 同一 | Pass |
| Hot 100 | 94→1→42→74 | 同一 | Pass |
| YouTube差分 | +1,309,266 | 約131万増と丸め | Pass |
| 調性 | Dm／Cm競合、未解決 | 断定なし | Pass |
| 解釈 | 作者意図と区別 | 批評的解釈／唯一の正解ではないと注記 | Pass |

## 3. 自動チェック結果

- Claim数: 43。
- Claim ID: CE-001〜CE-043、連番、重複なし。
- Claim-Evidence TableのMarkdown / CSV ID: 完全一致。
- 定義Source数: 61。
- 未定義Source ID参照: 0。
- YouTube差分: 13,450,222 − 12,140,956 ＝ 1,309,266。
- 観測間隔: 約24.3167日。
- 単純日平均: 約53,842回／日。報告書の「約5.38万回／日」と一致。
- Public Report文字数: 約4,500字。見出し6節以上を持ち、Evidence Reportの単純要約ではない。
- Public Report内URL: 14件、すべてReferences / Source Inventoryに登録済み。
- Public Report内のDm／Cm確定記述: 0。

## 4. エビデンス境界

### 確定して採用

- 商品情報、公開日、主要クレジット、初披露、11名、公式センター方針。
- MV公式物語、4人／7体、1999年7月、担当スタッフ。
- Billboard JAPAN、Oricon、公式YouTube観測の数値。
- THE FIRST TAKE初出演、特別リアレンジ、同一演奏陣、正式配信。

### 限定付きで採用

- MV尺249秒／配信4:10は媒体差を併記。
- BPMは約147〜150の第三者機械推定。
- 最高難度は公式評価として記載。
- TikTok数は発表主体を明記し、定義不明とする。
- 4:3、時代記号、7月32日は直接全編ログではなく、公式Shorts・補助資料経由。

### 未解決のまま不採用

- 正式な調性、コード進行、確定BPM。
- 全歌割り、ハーモニー構成、録音セッション詳細。
- MVの全カット順・秒単位ショット分析。
- CDTV保存映像の具体的歌唱・隊形・放送ミックス。
- TikTok数値の厳密な母集団。
- 個別公開施策と売上・再生の因果寄与率。

## 5. 競合処理

1. センター: 一部二次資料の冨田菜々風センター表記ではなく、公式「センターという概念なし」を採用。場面上の視覚的焦点とは区別。
2. 調性: 自動判定Dm／Cmが競合するため確定しない。
3. セールス: Billboard実売、Oricon実売、レーベル出荷を別指標として保持。
4. 尺: API 249秒と配信4:10を矛盾として消去せず、媒体差として併記。
5. SNS: 1万件超／約5万件を同一定義の時系列として計算しない。

## 6. Google Drive配置検証

- 対象楽曲フォルダ直下に `research_status.md` と6サブフォルダが存在。
- `01_Sources`: 初期資料、最終Phase 2台帳、YouTube抽出CSVを確認。
- `02_Research`: 基本メタデータ、一次資料抽出を確認。
- `03_Analysis`: Phase 3の5領域、Phase 4制作文脈、Phase 5比較を確認。
- `04_Evidence`: Claim-Evidence Table 2形式、Evidence Report、References、Auditを確認。
- `05_Public`: Public Reportを確認。
- `99_Working`: Phase 0 Drive inventoryを確認。

## 7. 最終判定

必要成果物は揃い、主要Claimは一次・公式資料を優先して追跡可能である。Fact、Observation、Analysis、Interpretationの境界は監査済み。Evidence ReportとPublic Reportの主要事実・数値・留保に矛盾は検出されなかった。

直接音源／映像解析を完遂できなかった領域は明示的な未解決事項として残され、推測による補完は行われていない。したがって、本調査は記録された限界のもとで正常終了可能と判定する。
