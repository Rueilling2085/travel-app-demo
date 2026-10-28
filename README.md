# travel-app-demo

Spec Studio 的示範用 repo。旅遊 App「會員點數到期提醒」的情境，資料皆為虛構。

## 這裡有什麼

- **Issue #2**：客服反映點數沒用就過期 → PM 提出「到期提醒從 30 天改成 180 天」，加上 `needs-spec` 標籤後進入 Spec Studio
- **PR #1**：A6 到期提醒的實作；工程在這裡用 `/suggest` 留言，提出規格修改建議

## 和 Spec Studio 的關係

- Issue 加上 `needs-spec` → Spec Studio 收件匣收到需求，AI 分析影響範圍
- PM 存版後 → 影響摘要自動回寫到 Issue
- 工程在 PR 留 `/suggest` → 變成待核准建議；PM 核准後，PR 自動收到「已核准，寫入規格」
- PR 合併 → 對應元件在規格上標為已實作

工程不用換工具，規格的修改一律由 PM 核准後寫入。
