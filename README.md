# BEHIND-GENAI-CORE-CONCEPT-
A scalable, modular data ingestion pipeline for GenAI apps. Collects, preprocesses, and transforms data from diverse sources into high-quality datasets for LLM fine-tuning, RAG systems, and more.

BEFORE THAT GO THROUGH THIS LANGCHAIN PORTAL AND OPEN IT IN ANOTHER TAB FOR BEST WORKFLOW IN GENAI APPLICATION WITHOUT ANY ERROR 



https://python.langchain.com/v0.2/docs/integrations/document_loaders/

SHARING MY NOTES AS WELL ! AS A SHORT NOTES BUT YOU CAN GO THORUGH THAT AS WELL THE MORE IMPORTANT IS PRACTICAL IMPLEMENTATION  WHEN TALKING ABOUT THE GENAI APPLICATION.

THIS NOTES ALL ABOUT CORE CONCEPT OF BEHIND EVERY GENAI APPLICATION 
AND THIS REPOSITORY IS ALL ABOUT
 
MODULE 1 --------
STEP 1 ---------> DATA INGESTION 

STEP 2 ---------> DATA TRANSFORMATION (SPLITING TEXT)

#### Text Splitting from Documents- RecursiveCharacter Text Splitters
This text splitter is the recommended one for generic text. It is parameterized by a list of characters. It tries to split on them in order until the chunks are small enough. The default list is ["\n\n", "\n", " ", ""]. This has the effect of trying to keep all paragraphs (and then sentences, and then words) together as long as possible, as those would generically seem to be the strongest semantically related pieces of text.

- How the text is split: by list of characters.
- How the chunk size is measured: by number of characters.



#### How to split by character-Character Text Splitter
This is the simplest method. This splits based on a given character sequence, which defaults to "\n\n". Chunk length is measured by number of characters.

1. How the text is split: by single character separator.
2. How the chunk size is measured: by number of characters.

