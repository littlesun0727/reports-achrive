# Reports Archive

报告、评测结果和离线展示材料归档。

## 获取与展示

首次下载：

```bash
git clone https://github.com/littlesun0727/reports-achrive.git
cd reports-achrive
```

后续更新：

```bash
git pull --ff-only
```

用 Chrome 或 Edge 打开仓库根目录的 `index.html`，即可选择报告。报告支持本地离线展示，无需 Python、API Key 或服务器。请保留完整目录结构。

## 报告目录

| 日期 | 内容 | 本地入口 |
| --- | --- | --- |
| 2026-11-03 | Collage：Sol medium pixel 1000 张解析、137 张多模型对照、六项评测 | [打开报告目录](reports/2026-11-03/collage-demo/index.html) |

本次归档保留原图、预测框、详情页、结构 JSON 和评测报告。原始全量筛选图库不在本次范围内。教师自动标注不等于人工验收后的真值。

## 后续追加报告

1. 在 `reports/YYYY-MM-DD/<report-name>/` 下放置完整离线报告，图片和数据使用相对路径。
2. 更新此处的报告目录和根目录 `index.html`。
3. 提交并推送新增文件。大型报告分批提交、分批推送。

仓库是公开的，只提交计划公开的报告材料；不要加入密钥、凭据、环境配置或模型权重。已发布的报告按日期保留，修订版使用新目录，便于回溯。
