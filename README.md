# rag-evals-nextjs

Assistente RAG que responde perguntas sobre documentação técnica **citando as fontes**, com avaliação automática de qualidade (evals com **promptfoo** + **Ragas**) rodando no CI.

## Stack

- Next.js (App Router) + TypeScript + Tailwind CSS
- Vercel AI SDK
- Postgres + pgvector
- promptfoo e Ragas (evals)
- GitHub Actions (CI)

## Roadmap

- [ ] D1: Setup do projeto e corpus em `docs/`
- [ ] D2: Ingestão (chunking + embeddings) no pgvector e retrieval
- [ ] D3: Chat com tool calling e citação de fontes
- [ ] D4: RAG avançado (reranking) e métricas da RAG triad
- [ ] D5: Evals com promptfoo e LLM-as-judge
- [ ] D6: Ragas e evals no CI (GitHub Actions)
- [ ] D7: Polimento, deploy e divulgação

## Rodando localmente

```bash
npm install
npm run dev
```
