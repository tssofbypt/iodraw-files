# ioDraw 绘图文件

这里保存使用 ioDraw 制作的流程图源文件，主要包括大语言模型（LLM）、检索增强生成（RAG）相关流程，以及流程图示例。

## 文件索引

所有绘图源文件都保存在 [`all/`](all/) 目录中。

| 内容 | 源文件 | 说明 |
| --- | --- | --- |
| 无 RAG 流程 | [无RAG流程图.iodraw](all/无RAG流程图.iodraw) | 包含用户、问题、提示词与大语言模型等节点 |
| 模型问答步骤 | [未命名绘图.iodraw](all/未命名绘图.iodraw) | 包含输入问题、接收输入、编码与处理、生成回答四个步骤 |
| 标准 RAG 流程 | [未命名绘图.iodraw-1.iodraw](all/未命名绘图.iodraw-1.iodraw) | 包含嵌入模型、向量存储索引、数据库、上下文与答案 |
| 仅使用大模型的流程 | [未命名绘图.iodraw-2.iodraw](all/未命名绘图.iodraw-2.iodraw) | 展示查询直接输入大语言模型并生成答案 |
| 台灯故障排查示例 | [未命名绘图.iodraw.iodraw](all/未命名绘图.iodraw.iodraw) | 英文判断流程图，包含插电、检查灯泡、更换灯泡与维修等分支 |

表中的内容名称依据图内文字整理；源文件保留原有名称，便于继续查找和编辑。

## 查看与编辑

`.iodraw` 文件是可编辑的绘图源文件。点击索引可以查看文件；查看图形或继续编辑时，可下载源文件并用 [ioDraw 流程图编辑器](https://www.iodraw.com/diagram) 打开。

## 保存约定

- 现有绘图保留在 `all/` 目录，继续沿用原文件名。
- 新增绘图使用能说明内容的名称，例如 `RAG-检索流程.iodraw`。
- 新增文件后，在上面的索引中补充一行说明。

## ioDraw 格式入口

以下是原有的格式入口；本仓库目前保存的是 `.iodraw` 文件。

- [流程图](https://www.iodraw.com/diagram)：`.iodraw`
- [思维导图](https://www.iodraw.com/mind)：`.mind`
- [甘特图](https://www.iodraw.com/gantt)：`.gantt`
- [在线白板](https://www.iodraw.com/whiteboard)：`.wb`
- [代码绘图](https://www.iodraw.com/codechart)：`.md`
- [在线图表](https://www.iodraw.com/chart)：`.chart`
