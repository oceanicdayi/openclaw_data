# OpenClaw 長期記憶

這個檔案保存重要的長期記憶，不是 raw 日誌。

## Token 配置

### GitHub Token
- **位置**：`/root/.openclaw/openclaw.json` -> `GITHUB_TOKEN`
- **用途**：Git 操作、GitHub API 存取
- **安全提醒**：請勿將實際 token 公開到本檔案

## 重要網址與資源

- OpenClaw 官方文件：/usr/local/lib/node_modules/openclaw/docs
- 線上文件：https://docs.openclaw.ai
- GitHub 設定：https://github.com/settings/tokens

## 工作流程

### 每個 Session 開始時
1. 讀取 `SOUL.md` - 確認我的身份和核心原則
2. 讀取 `USER.md` - 了解幫助對象
3. 讀取 `memory/YYYY-MM-DD.md` - 今日/昨日記錄
4. **如果是在 main session**：讀取 `MEMORY.md` - 長期記憶

## 項目位置

- 主工作目錄：`/root/.openclaw/workspace/`
- 配置目錄：`/root/.openclaw/`
- Openclaw_dayi 倉庫：`/root/.openclaw/workspace/Openclaw_dayi/`

## 待更新（定期檢查）

- 重要事件 → 加入 `memory/YYYY-MM-DD.md`
- 有價值的記憶 → 整合到本檔案
- 需要記住的決策 → 記錄在對應檔案

---

_最後更新：2026-02-21_
