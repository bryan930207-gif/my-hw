# demyst-co-pilot 內部營運初始化 Brief (Mission 0)

## 專案背景
- **名稱**：demyst-co-pilot (解密伴航顧問公司)
- **階段**：系統建立與初期營運初始化。
- **背景**：由大同大學資工系大三學生 Zhang Kaiming 創立，旨在為非技術背景創辦人提供 AI 技術伴航。

## 核心目標
- 建立一套自動化的 Agent 協作系統。
- 確保諮詢流程符合「技術解密」與「風險降低」的核心價值。
- 完成內部三位專家 Agent 的職責校準。

## 核心規格 (依據 spec.md)
[此處引用 spec.md 之完整規格，包含 A 至 E 區所有內容]
- **Specialists**: Cost Optimizer, Security Auditor, Integration Architect.
- **Workflow**: Intake -> Dispatch -> Integration -> Delivery.
- **Deliverables**: Strategic & Defensive Tech Report.

## 待解任務 (Deconstruction)
1. **成本控制任務**：針對 Gemini CLI 的 Token 消耗進行初步預估，設定內部監控紅線。
2. **安全防禦任務**：檢查當前專案目錄結構中的 `shared-memory` 隱私隔離機制，確保客戶資料不會意外洩漏。
3. **架構整合任務**：設計一套標準化的 Markdown 報告模板，確保三方專家產出可無縫整合。
