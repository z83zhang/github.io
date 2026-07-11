## Projects
### [Multimodal Search Pipeline](https://github.com/z83zhang/ai-data-engineering/tree/main/multimodal-search-pipeline)
Semantic search over meeting audio and slides using Whisper, Tesseract OCR, 
sentence-transformers, and ChromaDB. Includes WER and Precision@5 evaluation.  
**Tech:** Python · Whisper · Tesseract · ChromaDB 

### [Metric Intelligence Agent](https://github.com/z83zhang/ai-data-engineering/tree/main/metric_intelligence_agent)

An agentic tool that answers data questions for product managers 
and data scientists — in plain English, no SQL required.

At companies with mature data foundations, top-line metrics live 
in dashboards — but PMs and data scientists constantly need more: 
derived metric questions that require knowing the schema, canonical 
definitions, and which tables to trust. This tool answers them 
automatically — with a reflection loop that checks its own work 
before returning a trusted result.

**Tech:** Python · DuckDB · OpenAI gpt-4o · pandas

**Status:** ✅ Core agent complete · 🚧 LangGraph refactor in progress

