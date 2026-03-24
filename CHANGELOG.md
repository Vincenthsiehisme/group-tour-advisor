# CHANGELOG

- v0.1：初版，四層知識架構 + Full/Spot/Task Flag 三種觸發模式 + prd-writer / task-dispatcher 協作介面
- v0.2：加入團旅五段生命週期（lifecycle.md）、階段感知的 Step 0、依階段的知識層載入邏輯、跨階段銜接風險獨立欄位
- v0.3：全面加入三種確認標注（[雄獅規則－待確認] / [業界通例] / [需工程確認]）、確認後的 ✅ 更新機制
- v0.4：三項協作整合 —— system-boundaries.md 重構兩層引用 squad-scope.json；Risk Register 加 Squad 欄；Task Flag 格式對齊 task-dispatcher Phase 2
- v0.5：skill-reviewer 改善 —— Description 從 140 字壓縮至 75 字（移除協作說明）；知識標注說明抽成 annotation-guide.md 按需載入；版本記錄移至 CHANGELOG；補齊「與其他 Skill 的協作介面」章節標題；Step 1 跨階段判斷邏輯明確化
- v0.7：全面審查更新 ——
  **[P0] business-rules.md**：新增三個佔位區塊（五、取消費率結構 / 六、配額邏輯 / 七、付款訂金規則），各含 PM 確認清單與工程影響說明；原有章節五到七順序後移，重新編號至八至十。
  **[P0] annotation-guide.md**：加入第四種標注 `[需業務/法務確認]`，補齊與 business-rules.md 實際使用的一致性，並說明與 `[雄獅規則－待確認]` 的區分邏輯。
  **[P0] CHANGELOG.md**：補記本次更新（v0.7）。
  **[P1] destinations/index.md**：新增「目的地特定設計注意事項」區塊，收納帛琉飯店雙維度選配邏輯、關帛領隊揭露義務；對照表新增 `middle-east-south-asia-africa.md` 條目；地區概覽分拆更新。
  **[P1] product-conventions.md**：移除末尾兩條帛琉/關帛設計慣例（已移至 destinations/index.md），加入重導向說明。
  **[P1] destinations/other-regions.md**：中東、南亞、非洲（埃及）區塊拆出；frontmatter 更新 scope 與 note；末尾加入拆出說明。
  **[P1] destinations/middle-east-south-asia-africa.md**：新建檔案，收錄原 other-regions.md 的中東/南亞/非洲區塊（埃及、土耳其、杜拜、印度、尼泊爾、斯里蘭卡）＋亞非通用注意事項＋高頻客訴來源表。
  **[P2] references/confirmation-log.md**：新建集中追蹤表，彙整所有 reference 檔案的 `[待確認]` 條目，含 BR/RF/SB/DE 四類，共 36 條，按優先度排列。
  **[P2] SKILL.md**：Reference Files 區塊更新——destinations 新增 middle-east-south-asia-africa.md；工具性參考新增 confirmation-log.md；annotation-guide 描述由「三種」改為「四種」。
