# academic_prompts
> 参考https://github.com/binary-husky/chatgpt_academic
学术常用的prompts
- 中文学术润色：作为一名中文学术论文写作改进助理，你的任务是改进所提供文本的拼写、语法、清晰、简洁和整体可读性，同时分解长句，减少重复，并提供改进建议。请只提供文本的更正版本，避免包括解释。请编辑以下文本
- 英语学术润色：Below is a paragraph from an academic paper. Polish the writing to meet the academic style,improve the spelling, grammar, clarity, concision and overall -readability. When necessary, rewrite the whole sentence. Furthermore, list all modification and explain the reasons to do so in markdown table.\n\n
- 查找语法错误：Can you help me ensure that the grammar and the spelling is correct? Do not try to polish the text, if no mistake is found, tell me that this paragraph is good. If you find grammar or spelling mistakes, please list mistakes you find in a two-column markdown table, put the original text the first column, put the corrected text in the second column and highlight the key words you fixed.\nExample:\nParagraph: How is you? Do you knows what is it?\n| Original sentence | Corrected sentence |\n| Original sentence | Corrected sentence |\n| :--- | :--- |\n| Do you **knows** what **is** **it**? | Do you **know** what **it** **is** ? |\nBelow is a paragraph from an academic paper. You need to report all grammar and spelling mistakes as the example before.\n\n
- 中译英：Please translate following sentence to English, making it more accureate and academic:
- 英译中：把下面的句子翻译成地道的中文，使它更加学术化：
- 学术中英互译：I want you to act as a scientific English-Chinese translator, I will provide you with some paragraphs in one language and your task is to accurately and academically translate the paragraphs only into the other language. Do not repeat the original provided paragraphs after translation. You should use artificial intelligence tools, such as natural language processing, and rhetorical knowledge and experience about effective writing techniques to reply. I'll give you my paragraphs as follows, tell me what language it is written in, and then translate:\n\n
- 找图片：我需要你找一张网络图片。使用Unsplash API(https://source.unsplash.com/960x640/?<英语关键词>)获取图片URL，然后请使用Markdown格式封装，并且不要有反斜线，不要用代码块。现在，请按以下描述给我发送图片：\n\n
- 解释代码：请解释以下代码：```代码块```
