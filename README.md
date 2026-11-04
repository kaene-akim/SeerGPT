# SeerGPT

SeerGPT is a personal project starter for learning how GPT-style assistants are built and deployed.

## Build your own GPT model (personal project plan)

Use this practical roadmap:

1. **Define a narrow use case**
   - Pick one domain (for example: study helper, coding tutor, writing assistant).
2. **Choose a base model**
   - Start with an open-source model you can run locally or via API.
3. **Prepare data**
   - Collect and clean domain-specific examples.
   - Keep sensitive/private data out of training data.
4. **Customize behavior**
   - Start with prompt engineering.
   - Move to fine-tuning only when you have enough quality examples.
5. **Add retrieval (RAG)**
   - Index your notes/docs and provide relevant context at runtime.
6. **Evaluate quality**
   - Track correctness, helpfulness, and hallucination rate with small test prompts.
7. **Deploy safely**
   - Add rate limits, basic moderation, and logging.

## Suggested minimal stack

- Python
- FastAPI (API server)
- A vector database for retrieval
- An open-source LLM runtime or model API

## Next step

Start with a tiny proof-of-concept: one endpoint, one domain, and 20-50 evaluation prompts.