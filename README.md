# 新兴产业周报：查新闻

西部证券新兴产业周报里，检索并填写 5 个新闻表的 Cursor skill。不含任何人的密钥。

## 同事怎么用

1. 把这个文件夹放到自己电脑的 `~/.cursor/skills/emerging-weekly-news/`。
2. 按同花顺官方说明单独安装 `ifind-finance-data`，把**自己的** iFinD MCP 密钥写进该 skill 的 `config/mcp_config.json`。不要把密钥放进本仓库。
3. `template/` 里有原版自动更新版 Excel 和完整版 PPT。新的一周把它们复制到周报文件夹，文件名改成这周的周日日期。不要从零新建。
4. 在这个文件夹里说：「按新兴产业周报查新闻的 skill，做这 5 个表。」下周展望做到 PPT 第 6 页，并在 Excel 里写好来源和截图。把这一页贴进 Excel 由人自己做。

## 这个 skill 做什么

只填这 5 张表：`主题技术面 ` 的基本面变化、`基本面变化底稿`、`下周展望 `、`产业聚焦 `、`产业聚焦底稿`。

- 基本面变化和产业聚焦：用 iFinD MCP 查这一周的新闻和公告。
- 下周展望：只从 https://wallstreetcn.com/calendar 取下一周的事件。

不拉万德数据，不打分，不做 PPT。
