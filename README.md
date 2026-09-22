# NAIprompt

自然语言 → NAI Prompt 编译器。

## V0.1

当前先完成一个纯前端、无需后端即可运行的原型：

- 自然语言基础解析
- 1boy / 1girl / solo 等基础标签
- 角色管理器（localStorage）
- 角色外貌缺失时保留 [APPEARANCE]
- 基础自动权重
- 张力 / 电影感 / 孤独感视觉意图
- 基础镜头与构图词自动补全
- 移动端适配

## 后续架构

目标不是做简单的中文词典翻译，而是：

自然语言
→ 场景结构化
→ 角色锚定
→ 属性作用域
→ 动作冲突检测
→ 视觉意图推断
→ 镜头/构图补全
→ 自动权重
→ NAI Prompt 编译

后续再加入真正的 AI 语义解析/API，以及更完整的 NAI 标签词库。


## 一键部署到 Render

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/1614130601zjs-del/NAIprompt)

点击上面的按钮即可将前端作为 Render Static Site 部署。