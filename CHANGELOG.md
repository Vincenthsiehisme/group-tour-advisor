# CHANGELOG

- v0.1：初版，四層知識架構 + Full/Spot/Task Flag 三種觸發模式 + prd-writer / task-dispatcher 協作介面
- v0.2：加入團旅五段生命週期（lifecycle.md）、階段感知的 Step 0、依階段的知識層載入邏輯、跨階段銜接風險獨立欄位
- v0.3：全面加入三種確認標注（[雄獅規則－待確認] / [業界通例] / [需工程確認]）、確認後的 ✅ 更新機制
- v0.4：三項協作整合 —— system-boundaries.md 重構兩層引用 squad-scope.json；Risk Register 加 Squad 欄；Task Flag 格式對齊 task-dispatcher Phase 2
- v0.5：skill-reviewer 改善 —— Description 從 140 字壓縮至 75 字（移除協作說明）；知識標注說明抽成 annotation-guide.md 按需載入；版本記錄移至 CHANGELOG；補齊「與其他 Skill 的協作介面」章節標題；Step 1 跨階段判斷邏輯明確化
- v0.6：目的地知識層重構 —— 原 destination-rules.md（紐澳/大陸港澳/美加）拆分為 destinations/ 子資料夾架構；新增 northeast-asia.md（日本/韓國，含飯店規格地雷/沖繩合車/韓國購物站/攝影師規則）；新增 southeast-asia.md（越南/柬埔寨/馬來西亞/新加坡/印尼/菲律賓，含簽證矩陣/巴里島安寧日/適合客群/常見問題）；新增 destinations/index.md 作為目的地→檔案對照索引；SKILL.md Step 1 加入目的地分流載入邏輯，避免全量載入
