# consulting-ppt

把材料做成一套咨询报告风格的 16:9 演示页图片。方法来自 [ppter](https://github.com/fanyong1988/ppter)：先确认受众、页数和必须保留的事实，再按固定字段写出每一页，用同一套咨询报告视觉逐页生成整页画面。

安装后对 Codex 说：

> 把下面的方案做成 8 页咨询报告画面，受众是客户管理层。

## 安装

```bash
gh skill install fanyong1988/consulting-ppt consulting-ppt --agent codex
```

在 Codex 里也可以让 `$skill-installer` 从 `fanyong1988/consulting-ppt` 安装路径 `skills/consulting-ppt`。

手动安装时，把 `skills/consulting-ppt` 复制到下面其中一个目录：

- `~/.codex/skills/consulting-ppt`
- `~/.agents/skills/consulting-ppt`

## 结果

一个目录，里面是 `prompts.txt` 和按页码排列的 PNG。每一张是整页画面。

Codex 所在环境没有图像工具时，结果只有 `prompts.txt`，并会说明画面还没有生成。

## 许可

[MIT](LICENSE)。
