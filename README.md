# data-pipeline
Pipeline xử lý dữ liệu thô cho AI Agent (RAG).
- Ingestion PPTX/PDF/Word/HTML (Unstructured; PPTX qua pptx-tools MCP, fallback python-pptx)
- Chunking slide-aware (LlamaIndex) · Embedding + Qdrant (embedded) · Agentic RAG (LangGraph)
- Bridge stdio→Streamable HTTP cho MCP server (`scripts/pptx_mcp_bridge.sh`)
