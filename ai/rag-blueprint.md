# RAG (Retrieval-Augmented Generation) Blueprint

## Pattern

1. **Embed** – Store your domain knowledge in a vector database.
2. **Retrieve** – Match queries against relevant chunks.
3. **Generate** – Let the LLM respond with context, not hallucination.

## My Notes

* Lightweight embeddings (bge-base-en) scale better than massive ones for most business use cases.
* Always split short-term vs. long-term knowledge bases.

  * Short-term = fast-changing stuff (tickets, recent deals).
  * Long-term = policies, playbooks, historical data.
* Weekly fine-tuning beats giant one-off training runs. Incremental > firehose.

## Principle

RAG isn’t magic. It’s plumbing. Get the pipes right, and your answers flow. Screw it up, and you drown in garbage.
