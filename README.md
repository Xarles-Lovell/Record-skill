# Record skill

Record 用来在项目进行到某个节点时，整理一份持续更新的项目记忆。它记录具体事实，也记录知识卡点、反复提问、纠正 AI 和返工原因，方便以后复盘、介绍项目和准备发布内容。

## 怎么放文件

每个项目根目录只放一个 `Record.md`，和 `README.md` 类似。不要在子文件夹创建新的记录文件。`Record/` 文件夹只存放这个 skill 的说明、模板和测试资料。

## 怎么触发

在 Codex 里说“Record 一下”“记录一下”或“整理记录一下”。也可以直接说“使用 Record skill”。你决定什么时候记录，AI 不会自行判断项目是否结束。

## 会记录什么

- 需要 AI 帮忙捋清的知识点；
- 项目里反复问的问题；
- 反复纠正 AI、调整或返工的地方；
- 各阶段的实际事实、日期、成果和选题。

## 日期和修改

无法确认日期时会标记“实际日期待补充”，不会猜日期。发现旧记录可能有误时，AI 会先询问你；你确认后才修改。

## Mermaid 图

默认使用 Mermaid 阶段图。Obsidian 可以直接预览；也可以在 [Mermaid Live](https://mermaid-live.nodejs.cn/) 或 [jyshare](https://www.jyshare.com/front-end/9729/) 查看和导出。你可以要求改成纯文字。

## 模板

复制 [`templates/Record.md`](templates/Record.md) 到项目根目录，并改名为 `Record.md`。如果文件已经存在，直接让 AI 读取并整理，不要再创建第二份。
