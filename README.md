OntologyMapperAI
🚀 OntologyMapperAI is an AI-powered ontology mapping solution that aligns concepts across different industrial ontologies using a hybrid approach combining embedding-based, ontology-based, and hybrid similarity methods.

Key Features:
✅ Exact Match Detection – Identifies 1:1 class matches based on names.
✅ Embedding-Based Similarity – Uses AWS Bedrock's Titan Embeddings to compute semantic similarity between ontology concepts.
✅ Ontology-Based Similarity – Implements rule-based methods (Levenshtein, Jaccard, and ontology relationships).
✅ Hybrid Approach – Combines AI embeddings with ontology-based rules for improved accuracy.
✅ Contextual Mapping – Extracts relationships (subClassOf, relatedTo, definitions) to enhance mapping quality.
✅ Automated Report Generation – Saves results in an Excel file for review.

Tech Stack:
Python (for data processing & AI models)
AWS Bedrock (amazon.titan-embed-text-v2:0 for embeddings, anthropic.claude-3-sonnet-20240229-v1:0 for prompts)
RDFLib (for ontology parsing)
Pandas & OpenPyXL (for structured data output)
GitHub Actions (Optional) for automation
Use Case:
Ideal for industrial ontologies, enabling AI-driven ontology alignment to streamline data integration across different standards (e.g., CFIHOS, MLP204).