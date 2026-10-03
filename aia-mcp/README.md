# AIA MCP 研發處資料線（patch）

`0001-mcp-ord-vertical-slice.patch` 是要套到 https://github.com/aintpu/ntpu-ai-assistant 的修改
（新增 `mcp/` 資料夾、兩個 GitHub Actions workflow、README 一段說明），基準 commit 為 `a7957e4`。

套用方式：

```bash
git clone https://github.com/aintpu/ntpu-ai-assistant
cd ntpu-ai-assistant
git checkout -b claude/project-thread-h9pje7
git am /path/to/0001-mcp-ord-vertical-slice.patch
```
