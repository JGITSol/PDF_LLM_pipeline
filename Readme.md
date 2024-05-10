# PDF to LLM pipeline
## Version 0.0.1 Pre-alpha
- expect nothing working, might stil dissapoint
### Roadplan:
  - straight pipe for nice documents, fed directly into LLM (yes, I know - planned 200k Token context message~, you know how accurate it will be)
  - accuracy improvement from expected pollock to something readable
  - Will pin an article to go with this repo, tests should be hilarious
  - Aimed at totally unknown context of Polish Law, datasets will be at my Huggingface in recent future.
    *Depending on the results next parts may vary, but should be mostly the same
  - straight pipe for bad documents (OCR integration)
  - bent pipe for COT(Chain of Thought) and Chroma (Vector DB)
  - assimilation into enhanced RAG
    *With enough funding and prospective evaluation who knows, maybe a finetune?
      2405.00732 - arxiv paper that gives hope for small models, good eval of previous gen models(before LLAMA3 and phi-3)
