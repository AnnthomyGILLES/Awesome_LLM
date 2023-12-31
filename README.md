

# Awesome LLM - Personal review
## Background
- [Visualizing A Neural Machine Translation Model (Mechanics of Seq2seq Models With Attention)](https://jalammar.github.io/visualizing-neural-machine-translation-mechanics-of-seq2seq-models-with-attention/)
- [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/)
- [Primers • Overview of Large Language Models](https://vinija.ai/models/LLM/)

## Vector databases
 - [Vector databases (Part 1): What makes each one different?](https://thedataquarry.com/posts/vector-db-1/)
 - [Vector databases (Part 2): Understanding their internals](https://thedataquarry.com/posts/vector-db-1/): The article delves into the rising significance of vector databases in the era of Large Language Models (LLMs) like ChatGPT. While LLMs can generate coherent text, they sometimes produce inaccurate results. Vector databases, which store data as vectors, can be combined with LLMs to provide more accurate and up-to-date information. The piece also touches on the technical aspects of vector databases, including embeddings, similarity computation, indexing, and the potential of hybrid search systems that combine traditional keyword and vector searches.

## Theoretical Understanding

### Transformer and Attention
- [À la découverte du Transformer | Le Data Scientist](https://ledatascientist.com/a-la-decouverte-du-transformer/)
- [Transformer’s Encoder-Decoder](https://kikaben.com/transformers-encoder-decoder/)
- [The Annotated Transformer](http://nlp.seas.harvard.edu/2018/04/03/attention.html): The Transformer model from "Attention is All You Need" has revolutionized NLP tasks. This article provides a streamlined, annotated implementation of the paper, consisting of 400 lines of code.

	
## LLMs Limitations & Challenges

 - [Open challenges in LLM research](https://huyenchip.com/2023/08/16/llm-research-open-challenges.html): The article delves into the current challenges and research directions concerning Large Language Models (LLMs). It highlights 10 key areas: 1) Reducing AI's tendency to fabricate information (hallucinations), 2) Optimizing context understanding and response generation, 3) Incorporating multiple data types like text and images (multimodality), 4) Enhancing LLMs' speed and cost-efficiency, 5) Designing new model architectures beyond the Transformer, 6) Exploring alternatives to traditional GPU-based deep learning, 7) Making AI agents that can perform tasks more usable, 8) Refining models' learning based on human preferences, 9) Improving the efficiency of chat interfaces, and 10) Developing LLMs for languages other than English.

## Build
 - [Building Scalable Large Language Model (LLM) Apps](https://ai.plainenglish.io/building-scalable-large-language-model-llm-apps-509894bc7f6a)
	 - The article delves into building scalable large language model (LLM) applications. It emphasizes FastAPI's benefits and Langchain's scalability challenges. It recommends vendor-provided VectorStores or using Redis and Qdrant for scalability, underscores the significance of semantic caching with GPTCache, and suggests Microsoft Guidance for controlled LLM outputs. For document processing, unstructured.io is highlighted as a top recommendation.
 - [🦜️ LangChain + Streamlit🔥+ Llama 🦙: Bringing Conversational AI to Your Local Machine 🤯](https://ai.plainenglish.io/%EF%B8%8F-langchain-streamlit-llama-bringing-conversational-ai-to-your-local-machine-a1736252b172)
	 - Integrating Open Source LLMs and LangChain for Free Generative Question Answering (No API Key required)
 - [All You Need to Know to Build Your First LLM App](https://towardsdatascience.com/all-you-need-to-know-to-build-your-first-llm-app-eb982c78ffac)
	 - Integrating Open Source LLMs and LangChain for Free Generative Question Answering (No API Key required)
- [Building LLM applications for production](https://huyenchip.com/2023/04/11/llm-engineering.html)
	- This post consists of three parts.
		- Part 1 discusses the key challenges of productionizing LLM applications and the solutions that I’ve seen.
		- Part 2 discusses how to compose multiple tasks with control flows (e.g. if statement, for loop) and incorporate tools (e.g. SQL executor, bash, web browsers, third-party APIs) for more complex and powerful applications.
		- Part 3 covers some of the promising use cases that I’ve seen companies building on top of LLMs and how to construct them from smaller tasks.
## Transformers
### For Computer Vision
### For Time Series
- [[Paper] Are Transformers Effective for Time Series Forecasting?](https://arxiv.org/abs/2205.13504)
- [[Paper] Temporal Fusion Transformers for Interpretable Multi-horizon Time Series Forecasting](https://arxiv.org/abs/1912.09363)
- [Yes, Transformers are Effective for Time Series Forecasting (+ Autoformer)](https://huggingface.co/blog/autoformer)
The article discusses the effectiveness of Transformers for Time Series Forecasting, referencing the award-winning Informer model and the newer Autoformer model. Empirical evidence suggests that Transformers outperform the simple linear model, DLinear, contrary to some claims.

## Applied LLMs
### in medicine
 - [Large language models in medicine: the potentials and pitfalls](https://arxiv.org/abs/2309.00087): The paper explores the potential of large language models (LLMs) like ChatGPT in medicine. While they show promise in tasks like patient queries and medical documentation, they also have challenges like biases and privacy concerns. Solutions include domain-specific models and human oversight. The paper details LLM technicalities, provides guidance on medical applications, and emphasizes the need for rigorous evaluation. Healthcare professionals are urged to stay informed about LLM advancements.
