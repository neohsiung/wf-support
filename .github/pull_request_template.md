<!-- 由 dev-standard v0.23.2 產生，請勿手改；要改請改 dev-standard 的 components/pr-template，再跑 sync.py update -->
風險級：<R0|R1|R2|R3>   <!-- R3（動錢、正式環境）agent 不動手，只提案；見 dev-standard §2 -->

Refs #<issue>   <!-- 完整做完才用 Closes #N；只做一部分用 Refs #N 並在 issue 留言剩什麼 -->

## 做了什麼

## 驗證
<!-- 每個「系統在某情況會怎樣」的說法都附可重跑的指令。跑不了的寫成推論並說明依據。 -->

## 回滾方式
<!-- R2／R3 必填 -->

## 檢查清單
- [ ] 綠燈（`.claude-task/green.sh` 或本 repo 的測試指令）
- [ ] `python3 .dev-standard/sync.py check` 通過
- [ ] 沒有新增 lint 違規（baseline 以外）
- [ ] 重構與行為改變在不同 commit；重構的 commit 沒有改測試
- [ ] 改了門檻、規則或契約 → 同一個 commit 附 DD
- [ ] 文件沒有寫會漂移的數字
- [ ] 依 [審查清單](https://github.com/neohsiung/dev-standard/blob/main/templates/review-checklist.md) 自查過設計原則

DERIVED: <這次學到、以後每個任務都該遵守的約束，以及它落在哪裡（規則檔／守衛測試／地雷編號）>　通用：<是｜否>
<!-- 通用：是 → 同一週對 dev-standard 開回填 PR，連回這個 PR -->
