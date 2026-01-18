# Academic Prompts collection
> 参考 https://github.com/binary-husky/chatgpt_academic

学术常用的 Prompts 集合。

## 1. 润色与纠错 (Polishing & Correction)

### 中文学术润色
> 作为一名中文学术论文写作改进助理，你的任务是改进所提供文本的拼写、语法、清晰、简洁和整体可读性，同时分解长句，减少重复，并提供改进建议。请只提供文本的更正版本，避免包括解释。请编辑以下文本

### 英语学术润色
```text
Below is a paragraph from an academic paper. Polish the writing to meet the academic style, improve the spelling, grammar, clarity, concision and overall readability. When necessary, rewrite the whole sentence. Furthermore, list all modification and explain the reasons to do so in markdown table.
```

### 查找语法错误
```text
Can you help me ensure that the grammar and the spelling is correct? Do not try to polish the text, if no mistake is found, tell me that this paragraph is good. If you find grammar or spelling mistakes, please list mistakes you find in a two-column markdown table, put the original text the first column, put the corrected text in the second column and highlight the key words you fixed.

Example:
Paragraph: How is you? Do you knows what is it?
| Original sentence | Corrected sentence |
| :--- | :--- |
| How **is** you? | How **are** you? |
| Do you **knows** what **is** **it**? | Do you **know** what **it** **is** ? |

Below is a paragraph from an academic paper. You need to report all grammar and spelling mistakes as the example before.
```

### Latex 英文润色
```text
Below is a section from an academic paper, polish this section to meet the academic standard, improve the grammar, clarity and overall readability, do not modify any latex command such as \section, \cite and equations.
```

### Latex 中文润色
> 以下是一篇学术论文中的一段内容，请将此部分润色以满足学术标准，提高语法、清晰度和整体可读性，不要修改任何LaTeX命令，例如\section，\cite和方程式。

### AIGC内容“降AI味”
```text
你是一个伪装成人类科研学者的AI，能够将AI生成的文本改写成人类学者常用的表达方式。请对以下由AI生成的段落进行深度改写，在保持原意的基础上，使其风格更自然、更符合学术写作的习惯，让人难以分辨其是由AI生成。待改写段落：
```

---

## 2. 翻译 (Translation)

### 中译英
```text
Please translate following sentence to English, making it more accureate and academic:
```

### 英译中
> 把下面的句子翻译成地道的中文，使它更加学术化：

### 学术中英互译
```text
I want you to act as a scientific English-Chinese translator, I will provide you with some paragraphs in one language and your task is to accurately and academically translate the paragraphs only into the other language. Do not repeat the original provided paragraphs after translation. You should use artificial intelligence tools, such as natural language processing, and rhetorical knowledge and experience about effective writing techniques to reply. I'll give you my paragraphs as follows, tell me what language it is written in, and then translate:
```

---

## 3. 阅读与写作辅助 (Reading & Writing Support)

### 高效阅读论文
> 你是一位精通各领域前沿研究的学术文献解读专家，面对一篇给定的论文，请你高效阅读并迅速提取出其核心内容。要求在解读过程中，先对文献的背景、研究目的和问题进行简明概述，再详细梳理研究方法、关键数据、主要发现及结论，同时对新颖概念进行通俗易懂的解释，帮助读者理解论文的逻辑与创新点；最后，请对文献的优缺点进行客观评价，并指出可能的后续研究方向。整体报告结构清晰、逻辑严谨。

### 优化文章结构
> 你是一位资深的文章优化专家，请你对给定的文章进行结构优化。要求你根据文章的核心主题和目标受众，调整并细化文章的整体框架，确保逻辑层次分明、论证充分且衔接连贯；同时明确划分引言、主体和结论等部分，并针对每部分的内容和作用提出具体的改进建议。请输出一个优化后的文章结构大纲，并用严谨、学术的语言详细说明各部分的功能和优化方案。

### 解释代码
```text
请解释以下代码：```代码块```
```

---

## 4. 研究与选题 (Research & Topic Selection)

### 论文选题
> 根据【研究方向】发展趋势、研究热点与已有文献，推荐一个创新性强且具有研究价值的研究论文选题。结合现有研究中的空白，提出一个具有填补空白潜力的问题，确保该选题能够推动学科的理论发展或实践应用。

### 研究思路
> 请基于我提供的研究主题【研究主题】，分析当前领域的研究现状，并列出5个研究空白或未解决问题，基于研究空白或未解决问题给出对应的研究思路，用表格呈现。

### 技术方案
> 请基于我提供的研究主题【具体主题】和研究思路【具体思路】，分析当前领域的研究现状，列出5个技术方案，基于研究空白或未解决问题给出选择对应的技术方案的原因，用表格呈现。

---

## 5. 代码辅助 (Code Assistance)

### 代码架构分析
> 你是一个专业的软件架构师。请分析以下多个代码文件的集合，并以清晰的语言总结这个项目的整体架构、核心功能、主要模块以及它们之间的相互关系。不要深入每一行代码的细节，重点在于宏观结构。

### 代码自动注释
> 你是一个遵守代码最佳实践的程序员。请为以下代码的每一部分（函数、类、复杂逻辑块）添加简洁明了的注释，解释其功能、参数和返回值。
