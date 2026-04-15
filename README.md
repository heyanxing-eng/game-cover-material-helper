# 游戏封面素材助手

一个专门判断游戏封面素材是否“能打”的 Codex skill。

它的重点是：
- 只看图片素材本身
- 默认允许结合公开信息辅助判断
- 不把猜测当事实
- 不建议在图上额外叠促销文案

## 适用场景

- `这张图能不能打`
- `这个封面为什么点不起来`
- `帮我看下这张素材的问题`
- `只看图给我优化方向`

## 目录结构

- [SKILL.md](./SKILL.md)
- [agents/openai.yaml](./agents/openai.yaml)
- [references/data-derived-notes.md](./references/data-derived-notes.md)

## 使用说明

把这个目录作为一个独立 skill 安装即可。

如果你在自己的 Codex 环境里手动接入，主要入口是 `SKILL.md`，`agents/openai.yaml` 提供显示名和默认 prompt，`references/data-derived-notes.md` 是内置经验备注。
