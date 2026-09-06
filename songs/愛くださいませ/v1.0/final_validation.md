# Final Validation / Publication Audit — ≠ME「愛くださいませ」

- Research validation date: 2026-09-05
- Publication audit date: 2026-09-07
- Research result: **PASS WITH DOCUMENTED LIMITATIONS**
- Publication result: **PASS AFTER CORRECTIONS**

## 1. 公開成果物

| 成果物 | 状態 | 公開監査 |
|---|---|---|
| Public Report | 完成 | Pass |
| Evidence Report | 完成 | Pass |
| Claim–Evidence Table | 43 Claim | Pass |
| References / Source Inventory | S01–S51、YT01–YT04、C01–C05 | Pass |
| research_status | 完成 | Pass |

## 2. Evidence Report ↔ Public Report整合

| 検証軸 | 結果 |
|---|---|
| 公開順（05-16初披露、06-09配信、06-24発売） | Pass |
| 11名／公式「センターという概念なし」 | Pass |
| 作詞・作曲・編曲・演奏者 | Pass |
| 《幻想即興曲》オマージュの扱い | Pass |
| MVの4人の堕天使＋7体の人形、1999年7月 | Pass |
| 振付の公式評価と制作者コメント | Pass |
| Billboard / Oricon / Hot 100 | Pass |
| YouTube時点観測値 | Pass |
| 調性を未解決のまま保持 | Pass |
| 批評的解釈と作者意図の分離 | Pass |

## 3. Claim / Source整合

- Claim数: 43。
- Claim ID: CE-001〜CE-043、連番・重複なし。
- 公開Source定義数: 60。
- 未定義Source ID参照: 0。
- YouTube差分: 13,450,222 − 12,140,956 ＝ 1,309,266。
- 観測間隔: 約24.3日。
- 単純日平均: 約5.38万回／日。

## 4. 公開監査で修正した事項

1. **Position Shuffle**
   - 公式「Position Shuffle」を、メンバーの恒常的な役割情報の根拠とはしない。
   - Source Inventoryでは「公式『Position Shuffle』企画映像」と中立表記に修正。

2. **YouTube観測データの出典**
   - 内部の管理ファイルや保存先を出典として扱わない。
   - ≠ME公式YouTube上の公開値をYouTube Data API等で取得した時点観測として `YT01–YT04` に再定義。
   - 観測日時を明記し、可変値であることを保持。

3. **非公開ストレージ**
   - 公開Source Inventoryから非公開ストレージへの直接リンクを除去。
   - 公開成果物から内部管理ファイル名・保存先への依存を除去。

4. **映像著作物**
   - 公開・利用許諾を確認できない映像ファイルを、公開研究の出典・証跡として使用しない。
   - CDTVフルサイズ版については、公開告知から放送・披露の存在のみを確認し、具体的な歌唱・隊形・放送ミックスは未解決のまま保持。
   - 映像ファイルそのものはリポジトリへ格納しない。

5. **リンク品質**
   - Billboard JAPANの冨田菜々風コメント記事URLに含まれていた不要な空白エンコードを修正。

## 5. 著作権・公開境界

- 歌詞全文を格納しない。許諾歌詞を参照し、Public Reportでは要約・批評として扱う。
- MV、ライブ、テレビ番組等の映像ファイルを格納しない。
- 第三者記事本文を転載せず、出典リンクと要約・分析を使用する。
- 時点観測データは公開YouTube情報由来であることと観測日時を明示する。
- Fact / Observation / Analysis / Interpretationを区別する。

## 6. 未解決のまま公開する事項

- 正式な調性、確定BPM、コード進行。
- 全歌割り、ハーモニー構成、録音セッション詳細。
- MV全カットの秒単位ショット分析。
- CDTVフルサイズ版の具体的な歌唱・隊形・放送ミックス。
- TikTok数値の厳密な母集団。
- 個別施策と売上・再生の因果寄与率。

## 7. 最終判定

公開上の重大な問題として確認された、出典誤認、非公開ストレージへの直接参照、利用許諾を確認できない映像ファイルへの依存は修正・除外した。

公開版は、一次・公式資料を優先したClaim–Evidence構造を維持しつつ、第三者著作物そのものを再配布しない構成になっている。上記の未解決事項と批評的解釈の境界を明示することを条件に、**Public化可能**と判定する。
