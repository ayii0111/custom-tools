# custom-tools

Claude Code 索引式市場（index marketplace）。

本 repo 只存放 metadata，不含任何 plugin 程式碼；各 plugin 維護在自己的獨立 repo。

## 使用

```bash
/plugin marketplace add ayii0111/custom-tools
/plugin install custom-skills@custom-tools
```

## 維護

- **更新既有 plugin**：直接推送到該 plugin 自己的 repo，本 repo 不需變動。
- **新增 / 移除 / 搬遷 plugin**：編輯 `.claude-plugin/marketplace.json` 的 `plugins` 陣列。

使用者端以 `/plugin marketplace update` 取得最新索引，`/plugin update <name>` 取得 plugin 新版。

## 已收錄

| Plugin | Source |
| --- | --- |
| custom-skills | [ayii0111/custom-skills](https://github.com/ayii0111/custom-skills) |
| ccc-divider | [ayii0111/ccc-divider](https://github.com/ayii0111/ccc-divider) |
| exit-clean | [ayii0111/exit-clean](https://github.com/ayii0111/exit-clean) |
| collapse-code-block | [ayii0111/collapse-code-block](https://github.com/ayii0111/collapse-code-block) |
| power-stats | [ayii0111/power-stats](https://github.com/ayii0111/power-stats) |
| projectize | [ayii0111/projectize](https://github.com/ayii0111/projectize) |
