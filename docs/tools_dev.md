## ToolS for Developers
These are various resources and tools for developers. Normies get out reee.
### The basics
These are the basic repos related to llama-cpp.</BR></BR>
[GGML main repo](https://github.com/ggerganov/ggml)</BR>
This is the main repo for GGML. This is the model format for llama-cpp. This might be relevant for you if you do model training and conversion.</BR></BR>
[Llama-cpp main repo](https://github.com/ggerganov/llama.cpp)</BR>
The main llama-cpp repo. Check the pull request here for upcoming features.</BR></BR>
[Llama-cpp python bindings](https://github.com/abetlen/llama-cpp-python)</BR>
The llama-cpp python bindings. Can be used to run llama-cpp in chat and server mode. Has a decent api.
### Integration
Sometetimes you just don't want to reinvent the wheel.</BR></BR>
[Langchain](https://github.com/langchain-ai/langchain)</BR>
Python framework with integrations for many tools. Has support for llama-cpp-python and various other AI tools. Has support for embeddings and vector stores.</BR></BR>
[Chainlit](https://github.com/Chainlit/chainlit)</BR>
For constructing a UI for llm's. This is an easy drop in tool to create a basic ui. Uses python and typescript. Good for testing models and is compatible with langchain.
### VectorDb
Vector databases. You might need these for document embeddings.</BR></BR>
[ChromaDb](https://github.com/chroma-core/chroma)</BR>
A local vector store. Lightweight and easy to use. Has support in langchain.
### Grammar Builders
Llama-cpp has grammar option that can force the output to be in a specific format. You can use grammar builders to create the grammar files for the llm.
[Grammar builder for llama-cpp](https://github.com/IntrinsicLabsAI/grammar-builder)</BR>
Llama-cpp can be set to return output in specific format. This is a tool to create the format files more easily.</BR></BR>
[Another grammar builder for llama-cpp](https://github.com/adrienbrault/json-schema-to-gbnf)</BR>
Llama-cpp can be set to return output in specific format. This is a tool to create the format files more easily.
### Text Parsing and NER
Parsing entities like names or locations from text automatically. Nice for embeddings metadata.</BR></BR>
[Spacy](https://github.com/explosion/spaCy)</BR>
Spacy offers pretrained models and nice features for text processing.</BR></BR>
[Sentence Transformers for Spacy](https://github.com/explosion/spacy-transformers)</BR>
[Sentence Transformers](https://github.com/UKPLab/sentence-transformers)</BR>
Sentence transformers are a lightweight alternative to Spacy.</BR></BR>
[Doctran](https://github.com/psychic-api/doctran)</BR>
Tool for text processing.</BR></BR>
[Textacy](https://github.com/chartbeat-labs/textacy)</BR>
Tool for text processing.</BR></BR>
### Search Algorithms
[Bm25](https://github.com/dorianbrown/rank_bm25)</BR>
Search engine algorithms in python.</BR></BR>
### Model finetuning
For tuning the model. Get it?</BR></BR>
[Axolotl](https://github.com/OpenAccess-AI-Collective/axolotl)</BR>
The swiss armyknife of finetuning.</BR></BR>
[Mergekit](https://github.com/arcee-ai/mergekit)
Ah yes, the source of frankenmerges that keeps on giving. Putting several good things together makes for something even better. I think thats science or something.