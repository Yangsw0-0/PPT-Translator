# PPT-Translator

将英文 PPT、PPTX 或课件 PDF 逐页整理为中文学习版 PDF。翻译忠实于原文，并在独立的「解释与补充」部分说明难点；专业术语每次出现都标注英文，公式沿用原课件符号与步骤，图示尽量保留。

## 在其他 AI 中使用

将 [SKILL.md](SKILL.md) 的完整内容作为任务说明提供给 AI，再上传课件并指定需要翻译的页码或范围。使用的 AI 需要具备读取课件、生成 PDF 以及检查输出页面的能力。

示例：

> 请按照 SKILL.md 的要求，将这份英文课件翻译成中文学习版 PDF。处理全部页面。

## 在 Codex 中使用

将仓库文件夹复制到 Codex 的 `skills/ppt-translator` 目录，然后使用 `$ppt-translator` 调用。`agents/openai.yaml` 仅提供 Codex 界面显示信息；核心翻译规则都在 `SKILL.md`。
