# llm_resources
Information and resources on everything related about running large language models locally and their development

## For Beginners
These resources are for beginners to get basic understanding of machine learning and ai. The courses are in a subjective order of difficulty.</BR></BR>
[AI for Beginners](https://github.com/microsoft/ai-for-beginners)</BR>
This is a general course about AI for beginners by Microsoft. This course will intorcude you to core conspets like Neural Networks, Computer Vision and Neural Language Processing. Requires some basic python experience for assignments.</BR></BR>
[Generative AI for beginners](https://github.com/microsoft/generative-ai-for-beginners)</BR>
This is a simple course for beginners by Microsoft. It will walk you through the very basic consepts of generative AI. These lessons require almost no coding experience.</BR></BR>
[Basic Machine Learning Tutorial](https://github.com/microsoft/ML-For-Beginners)</BR>
This is a course for machine learning for beginners by Micorosoft. You will need some basic python coding experience. This course will focus more on model training and refinment.</BR></BR>
[NLP Course For Beginners](https://huggingface.co/learn/nlp-course/chapter1/1)</BR>
HuggingFace course for Neural Language Processing. This course goes deeper into language models and explains consepts like Transformers and Finetuning. Requires moderate level of python experience.</BR></BR>
[Foundational Machine Learning](https://developers.google.com/machine-learning/foundational-courses)</BR>
Google courses for machine learning. This is a somewhat more advanced course in Machine learning. 

## On Information
This resources go more into the weeds of machine learning and language models. You might want to save these until you get comfortable with the subject.
</BR></BR>
[Book: The Principles of Deep Learning Theory](https://arxiv.org/abs/2106.10165)</BR>
[Book: Mathematical Introduction to Deep Learning: Methods, Implementations, and Theory](https://arxiv.org/abs/2310.20360)</BR>
[Community Instructions: Finetune Lora on Llama-cpp](https://rentry.org/cpu-lora)</BR>
[Community Instructions: Another Lora finetune instructions](https://rentry.org/59xed3)</BR>
[Papers on Local Models](https://rentry.org/localmodelspapers)</BR>
[Arxiv Papers on Machine Learning](https://arxiv.org/list/cs.LG/pastweek?skip=0&show=250)</BR>
[Another Git repo of ml resources](https://github.com/underlines/awesome-ml)</BR>

## On The Tubes
Channels covering AI subjects</BR></BR>
[AI Explained](https://www.youtube.com/@aiexplained-official/videos)</BR>
[Dr Alan Thompson](https://www.youtube.com/@DrAlanDThompson/videos)</BR>
[Andrej Karpathy](https://www.youtube.com/@AndrejKarpathy/videos)</BR>

## On Reddit
Reddit channels on Neural Language Networks.</BR></BR>
[Local Llama reddit](https://www.reddit.com/r/LocalLLaMA/)</BR>
LocalLlama is related on the facebook llama leaks. The community figured out how to run llama locally and this gave birth to a community of enthusiasts. Things have moved on since then, but if you need instructions on how to run language models locally, then you might want to visit here.</BR></BR>
[Text Generation WebUI reddit](https://www.reddit.com/r/Oobabooga/)</BR>
Text Generation WebUI is a GUI tool for running language models locally. This tool is well liked and has a decent sized community.

## On models
You will eventually want to get your hands on some models and their info. HuggingFace is the community site for everything llm. By the people for the people. Remember to check some leaderboards for suggestions on good models.</BR></BR>
[Hugginface](https://huggingface.co/)</BR>
[TheBloke](https://huggingface.co/models?sort=modified&search=thebloke)</BR>
[Alpaca model info](https://docs.alpacaml.com/home/welcome)</BR>
[Open llm leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard)</BR>
[Big Code Models leaderboard](https://huggingface.co/spaces/bigcode/bigcode-models-leaderboard)</BR>

## On Prompts
Prompting is important to get good results from models. Great prompting may save poor models and bad promting could ruin excellent ones. See guides on general how to's and the leaked prompts for some "inspiration".</BR></BR>
[Prompting Guide](https://learnprompting.org/docs/intro)</BR>
[Another Prompting Guide](https://www.promptingguide.ai/)</BR>
[Pygmalion cards](https://booru.plus/+pygmalion)</BR>
[Chub AI](https://www.chub.ai/)</BR>
[Character Card Editor](https://zoltanai.github.io/character-editor/)</BR>
[Leaked Prompts](https://github.com/linexjlin/GPTs)</BR>
[More leaked prompts](https://github.com/LouisShark/chatgpt_system_prompt)</BR>

## On Tools
Text Generation WebUI is pretty good overall tool for running llm's. Installation can be a bit tehcical though.Text Generation WebUIText Generation WebUI</BR></BR>
[Text Generation WebUI](https://github.com/oobabooga/text-generation-webui)</BR>
[Text Generation WebUI Extensions](https://github.com/oobabooga/text-generation-webui-extensions)</BR>
[CensorBench](https://codeberg.org/jts2323/censorbench)</BR>

## On Tool for Developers
These are various resources and tools for developers. Normies get out reee.</BR></BR>
[GGML main repo](https://github.com/ggerganov/ggml)</BR>
This is the main repo for GGML. This is the model format for llama-cpp. This might be relevant for you if you do model training and conversion.</BR></BR>
[Llama-cpp main repo](https://github.com/ggerganov/llama.cpp)</BR>
The main llama-cpp repo. Check the pull request here for upcoming features.</BR></BR>
[Llama-cpp python bindings](https://github.com/abetlen/llama-cpp-python)</BR>
The llama-cpp python bindings. Can be used to run llama-cpp in chat and server mode. Has a decent api.</BR></BR>
[Langchain](https://github.com/langchain-ai/langchain)</BR>
Python framework with integrations for many tools. Has support for llama-cpp-python and various other AI tools. Has support for embeddings and vector stores.</BR></BR>
[Chainlit](https://github.com/Chainlit/chainlit)</BR>
For constructing a UI for llm's. This is an easy drop in tool to create a basic ui. Uses python and typescript. Good for testing models and is compatible with langchain.</BR></BR>
[ChromaDb](https://github.com/chroma-core/chroma)</BR>
A local vector store. Lightweight and easy to use. Has support in langchain.</BR></BR>
[Grammar builder for llama-cpp](https://github.com/IntrinsicLabsAI/grammar-builder)</BR>
Llama-cpp can be set to return output in specific format. This is a tool to create the format files more easily.</BR></BR>
[Another grammar builder for llama-cpp](https://github.com/adrienbrault/json-schema-to-gbnf)</BR>
Llama-cpp can be set to return output in specific format. This is a tool to create the format files more easily.</BR></BR>
[Spacy](https://github.com/explosion/spaCy)</BR>
Spacy offers pretrained models and nice features for text processing.</BR></BR>
[Sentence Transformers for Spacy](https://github.com/explosion/spacy-transformers)</BR>
[Sentence Transformers](https://github.com/UKPLab/sentence-transformers)</BR></BR>
[Doctran](https://github.com/psychic-api/doctran)</BR>
Tool for text processing.</BR></BR>
[Textacy](https://github.com/chartbeat-labs/textacy)</BR>
Tool for text processing.</BR></BR>
[Bm25](https://github.com/dorianbrown/rank_bm25)</BR>
Search engine algorithms in python.</BR></BR>

