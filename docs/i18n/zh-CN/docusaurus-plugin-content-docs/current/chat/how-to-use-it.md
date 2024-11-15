---
title: 聊天
description: 如何使用聊天
sidebar_label: 如何使用它
keywords: [如何, 使用, 聊天]
sidebar_position: 1
---

![chat](/img/chat.gif)

## 如何使用它

聊天方便向 LLM 寻求帮助，而不需要离开 IDE 。你发送一个任务给它，包含任何相关信息，它回复最可能完成那个任务的文本或代码。如果它没有给出你想要的，那么你可以发送追加的消息，来明确和调整它的建议，直到任务完成。

聊天最好用来理解和迭代代码或者作为搜索引擎查询的替代。

## 输入请求并按下回车

你发送一个问题给它，它回复答案。你告诉它解决一个问题，它提供一个解决方案。你请求一些代码，它生成代码。

## 高亮代码片段作为上下文

你使用鼠标选择代码片段，按下 `cmd/ctrl + L` (VS Code) 或 `cmd/ctrl + J` (JetBrains) 将它发送给 LLM ，然后让它给你解释，或者请求它以某种方式优化。

## 使用 @ 符号标记上下文

如果有来自代码库，文档， IDE 或其他工具的信息，你想要包含在上下文中，你可以输入 @ 来选择和包含它作为上下文。你可以在 [聊天上下文选择](context-selection.md) 中了解更多关于如何使用这个。

## 应用生成的代码到你的文件中

当 LLM 回复编辑到文件中，你可以点击 “应用” 按钮。这将更新编辑器中存在的代码，对建议的变更作出反应。

## 对于新的任务开始一个新的会话

一旦你完成任务，想要开始一个新的，按下 `cmd/ctrl + L` (VS Code) 或 `cmd/ctrl + J` (JetBrains) 来开始一个新的会话，确保只有下一个任务相关的上下文提供给 LLM 。

## 在不同的模型中切换

如果你配置了多个模型，你可以使用下拉框或按下 `cmd/ctrl + ’`在不同的模型中切换。