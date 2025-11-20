# RAGagent1
this n8n workflow creates a self-updating company knowledge base powered by Google Gemini and Pinecone. The Google Drive Trigger constantly monitors a folder. Convert the document into searchable vectors and indexes them in Pinecone. The trigger detects the change, and the workflow automatically re-indexes the new content.
