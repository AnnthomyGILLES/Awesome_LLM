
# Awesome LLM - Personal review
## Background
- [Visualizing A Neural Machine Translation Model (Mechanics of Seq2seq Models With Attention)](https://jalammar.github.io/visualizing-neural-machine-translation-mechanics-of-seq2seq-models-with-attention/)
- [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/)
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
## Transformers
### For Computer Vision
### For Time Series
- [[Paper] Are Transformers Effective for Time Series Forecasting?](https://arxiv.org/abs/2205.13504)
- [[Paper] Temporal Fusion Transformers for Interpretable Multi-horizon Time Series Forecasting](https://arxiv.org/abs/1912.09363)
- [Yes, Transformers are Effective for Time Series Forecasting (+ Autoformer)](https://huggingface.co/blog/autoformer)
The article discusses the effectiveness of Transformers for Time Series Forecasting, referencing the award-winning Informer model and the newer Autoformer model. Empirical evidence suggests that Transformers outperform the simple linear model, DLinear, contrary to some claims.
## Applied LLMs
### in medicine
 - [Large language models in medicine: the potentials and pitfalls](https://arxiv.org/abs/2309.00087): The paper provides an overview of large language models (LLMs) and their potential applications in medicine. LLMs like ChatGPT are pretrained on massive text datasets and can generate human-like text. They have shown promise for medical tasks like answering patient questions, aiding clinical documentation, and supporting medical education. However, LLMs have limitations including potential inaccuracies, biases, unpredictable outputs, and ethical concerns around privacy. Strategies to mitigate these issues include developing domain-specific models trained on curated medical datasets, human oversight, and careful prompt engineering. The paper discusses the model architectures, training approaches, and current medical LLMs. It provides tutorials on using ChatGPT for tasks like insurance letters and exam questions. Future directions include multimodal LLMs, increased accessibility, establishing regulations, and research into explainability. Overall, the paper cautions that while LLMs offer opportunities to augment clinician workflows, rigorous evaluation is needed before clinical use. It advises healthcare professionals to understand LLMs' capabilities and limitations as these technologies continue advancing.
