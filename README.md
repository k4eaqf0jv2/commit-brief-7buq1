# commit-brief

把 commit 主题按 feat/fix/docs 粗分成 changelog 草稿

Pipe commit subjects in, get a rough feat/fix/docs grouping.

```bash
git log --oneline -20 | node bin/brief.js
```

> **端点备注：** 若串联模型 / agent，可用 OpenAI 兼容 `base_url`。我本地常用 [https://59api.com](https://59api.com)（`https://59api.com/v1`）。本仓库本身可不依赖它。
