# Awesome Pinecone
> A curated list of awesome Pinecone resources, libraries, tools and applications

Feel free to improve this list by [contributing](CONTRIBUTING.md)!

## Resources
### Documentation
- [Quickstart](https://docs.pinecone.io/guides/get-started/quickstart) - Guide on how to set up and use Pinecone Database
- [Sample Notebooks](https://docs.pinecone.io/examples/notebooks) - Colab notebook walkthroughs
- [Sample Code](https://docs.pinecone.io/examples/sample-apps) - Sample applications
- [Architecture](https://docs.pinecone.io/guides/get-started/database-architecture) - Explanation of Pinecone architecture
- [Release Notes](https://docs.pinecone.io/release-notes/)

### Articles
- [What is a Vector Database?](https://www.pinecone.io/learn/vector-database/)
- [What is RAG?](https://www.pinecone.io/learn/retrieval-augmented-generation/)
- [What is Context Engineering?](https://www.pinecone.io/learn/context-engineering/)
- [How to Build a RAG Chatbot Without Coding](https://www.productcompass.pm/p/how-to-build-a-rag-chatbot)
- [Teaching Your AI to Read: A Guide to Scraping, RAG, and Smart Data Insights](https://hackernoon.com/teaching-your-ai-to-read-a-guide-to-scraping-rag-and-smart-data-insights)
- [Building an AI-Powered Discord Bot with Railway and Pinecone](https://blog.greenflux.us/building-an-ai-powered-discord-bot-with-railway-and-pinecone/)
- [Full RAG Chatbot in Slack](https://medium.com/@progeorgek/full-rag-chatbot-in-slack-623990db3a3b)
- [Populate Pinecone from a website using n8n](https://docs.n8n.io/advanced-ai/examples/vector-store-website/)
- [5 Ways to Automate Pinecone with Zapier](https://zapier.com/blog/automate-pinecone/)
- [AI Assistants with Document Retrieval (RAG) Using Pinecone](https://community.appsmith.com/content/blog/ai-assistants-document-retrieval-rag-using-pinecone)

### Videos
- [Getting Started with Pinecone](https://www.youtube.com/watch?v=H6kCi7esgw0) - Walkthrough of Quickstart notebook
- [Semantic Search and Reranking with Cohere and Pinecone](https://www.youtube.com/watch?v=e7x1wJlmDjs) - How to apply reranking to search pipelines
- [Why RAG Remains Essential for Modern AI](https://www.youtube.com/watch?v=buvRFJ-snAc) - Learn why RAG remains the backbone of agentic applications
- [Build Contextual Retrieval with Anthropic and Pinecone](https://www.youtube.com/watch?v=u-ocR-2P_YA)
- [Multi-Modal Semantic Search Starter Kit](https://x.com/itstomohiro/status/1937914182193541351)
- [RAG Upload Pipeline](https://www.linkedin.com/posts/madelineosman_friday-show-tell-building-a-custom-rag-ugcPost-7357069914320326657-484b/)
- [Hybrid RAG: Mastering Context By Combining GraphRAG and VectorRAG](https://www.youtube.com/watch?v=Xb_sIwlqZ0k) - Combining GraphRAG and VectorRAG using LangGraph, neo4j, and Pinecone
- [Pinecone Assistant API Overview](https://www.youtube.com/watch?v=_lXop0iYWYE)
- [Pinecone RAG Tutorial](https://www.youtube.com/watch?v=Jfo-gCmm46E)
- [Pinecone Database Overview](https://www.youtube.com/watch?v=X__6Zjltw48)
- [Building with Pinecone](https://www.youtube.com/watch?v=ZWBn_OxellE)
- [Pinecone Vector Search Deep Dive](https://www.youtube.com/watch?v=-08PKr8KJRY)

### Podcasts
- [Databases in Higher Dimensions](https://open.spotify.com/episode/3wexyIhxZuRCiV7gZovHh1) - Jack Pertschuk, Principal Engineer at Pinecone on Talking Serverless
- [AI, Ambition, and Innovation](https://open.spotify.com/episode/41KAUsK38UH5Ep49ZcG3xU) - Edo Liberty on Inside the ICE House

### Research
- [Efficient Constant-Space Multi-Vector Retrieval](https://www.pinecone.io/research/efficient-constant-space-multi-vector-retrieval/)
- [Unveiling DIME: Reproducibility, Scalability, and Formal Analysis of Dimension Importance Estimation for Dense Retrieval](https://www.pinecone.io/research/unveiling-dime-reproducibility-scalability-and-formal-analysis-of-dimension-importance-estimation-for-dense-retrieval/)

## Libraries
- [Python SDK](https://docs.pinecone.io/reference/python-sdk) - The Pinecone Python SDK is distributed on PyPI using the package name `pinecone`
- [NodeJS SDK](https://docs.pinecone.io/reference/node-sdk)
- [Java SDK](https://docs.pinecone.io/reference/java-sdk)
- [Golang SDK](https://docs.pinecone.io/reference/go-sdk)
- [.NET SDK](https://docs.pinecone.io/reference/dotnet-sdk)
- [Rust SDK](https://docs.pinecone.io/reference/rust-sdk)
- [context-window](https://github.com/hamittokay/context-window) - TypeScript RAG toolkit for ingesting documents, creating indexed collections with Pinecone, and querying them with OpenAI

## Tools
### Administration
- [Pinecone Embedding Atlas: Interactive Vector Visualization](https://github.com/martingaida/embedding_atlas) - Explore embeddings directly from a Jupyter notebook
- [Pinecone Explorer](https://github.com/stepandel/pinecone-explorer) - Desktop app for browsing, searching, and managing Pinecone indexes with support for semantic search and 13+ embedding providers

### Deployment
- [Terraform](https://docs.pinecone.io/integrations/terraform)
- [Pulumi](https://docs.pinecone.io/integrations/pulumi)

### Development
- [Pinecone Assistant MCP](https://github.com/pinecone-io/assistant-mcp)
- [Pinecone Developer MCP](https://github.com/pinecone-io/pinecone-mcp)
- [Infinite Context MCP](https://github.com/kayacancode/infinite-context-mcp) - MCP server that stores conversations and retrieves relevant context using Pinecone, reducing prompt bloat across chats and AI models

### Data Streaming
- [Kafka-To-Pinecone](https://ganeshsivakumar.github.io/langchain-beam/docs/templates/kafka-to-pinecone/) - A data streaming pipeline to consume real-time messages from kafka topic, generate embeddings using OpenAI and upsert vectors into Pinecone index. To support AI agents and RAG applications that continuously require fresh data. 

### Low-Code
- [Zapier](https://help.zapier.com/hc/en-us/articles/38950923151117-How-to-get-started-with-Pinecone-on-Zapier)
- [n8n Documentation](https://docs.n8n.io/integrations/builtin/cluster-nodes/root-nodes/n8n-nodes-langchain.vectorstorepinecone/)
- [n8n Templates](https://n8n.io/integrations/pinecone-vector-store/)

### Shell
- [Official Pinecone CLI](https://github.com/pinecone-io/cli)

### Misc
- [Chonkie](https://docs.chonkie.ai/python-sdk/handshakes/pinecone-handshake) - Chunking library integration with Pinecone

## Applications
- [Pinecone Assistant Demo](https://github.com/jayantarout79/jay-genai-portfolio/tree/main/pinecone_Assistant_demo) - RAG system using the Pinecone Assistant API to upload, index, and query PDF documents
- [Autonomous RAG Agent](https://github.com/Vyasss/autonomous-rag-agent) - Event-driven agent that routes queries between a Pinecone vector store and local file system using LangChain and Gemini