# SpaceWise
[![Supported Python Versions](https://badgen.net/pypi/python/black)](https://www.python.org/)

Large language models (LLMs) often generate responses with factual inaccuracies due to limited internal parametric knowledge. Retrieval-Augmented Generation (RAG) addresses some of these issues by adding external information to the prompt, but indiscriminate retrieval can lead to irrelevant or inaccurate responses. Furthermore, multilingual scenarios exacerbate these limitations, especially for minoritarian languages and niche domains like Space. To adapt LLMs to Space and create a multilingual assistant for Space stakeholders, SpaceWise proposes two main innovations. First, based on the SELF-RAG algorithm, SpaceWise enables an arbitrary LLM to assess the relevance of the retrieved information and to decide whether to add such information to the prompt based on such assessment. Additionally, SpaceWise integrates external translation capabilities in the LLM based on the Toolformer concept, addressing accessibility barriers for non-English speakers. 

## Background
SpaceWise is the natural continuation of our efforts to leverage LLM capabilities in the Space domain. Previously, we developed [SpaceQA](https://arxiv.org/abs/2210.03422), an open-domain extractive question answering (QA) system. SpaceQA utilizes language models to identify specific text fragments in a document collection that answer user queries. The system integrates a retriever component that identifies potential text passages where the answer could be found, placing it within the category of retrieval-augmented language models. However, SpaceQA lacks generation capabilities, and is limited to pointing out where the answer to the question lies in the text.

SpaceWise takes a step forward from the SpaceQA approach and embraces the power of generative language models. SpaceWise learns when to rely on its parametric knowledge acquired during pretraining and when it is better to utilize a retrieval system, depending on the user's query. 

We also worked with generative AI systems in the Space domain. [SpaceQQuiz](https://aclanthology.org/2022.inlg-demos.2/) employs sequence to sequence language models trained to generate questions and applied to the quality management domain in space operations. 

SpaceWise is a generative AI system that goes beyond generating questions and transcends language barriers. It is a fully-fledged conversational model capable of engaging in chat and following instructions. Moreover, SpaceWise can handle multiple languages using its parametric knowledge and, when necessary, resorting to machine translation tools.


## SpaceQA 
Recently, we collaborated with ESA to streamline access to information about early designs of space missions leveraging LLM. To this end we develop the QA system [SpaceQA](https://arxiv.org/abs/2210.03422) relying on a autoencoder model. SpaceQA has successfully enabled users to access information using questions in natural language that was previously available only in lengthy feasibility studies in PDF format. 

<p align="center">
<img src="https://github.com/expertailab/spacewise/blob/main/resources/images/spaceQA_diagram.png" alt="spaceQA high-level architecture" width="600"/>
  <br><em>High level components in SpaceQA</em>
</p>

### Demo

A demo of SpaceQA is available here (user/pass: sigir/s1g1r2022!): https://esatde.expertcustomers.ai/SpaceQA/

## SpaceQQuiz
We also developed a generative AI system to help the Quality Management department in ESA to generate automatically assesment material for evaluating training sessions. SpaceQQuiz leverages auto-regressive models like T5 and BART to generate questions, and a RoBERTa model to extract answers for such questions, thus verifying their suitability.

<p align="center">
<img src="https://github.com/expertailab/spacewise/blob/main/resources/images/spaceQQuiz.png" alt="spaceQA high-level architecture" width="600"/>
  <br><em>High level components in SpaceQquiz</em>
</p>

### Demo

A demo of SpaceQquiz is available here (user/pass: s demoINLG/demoINLG2022!): https://esatde.expertcustomers.ai/SpaceQQuiz/

## Contribution

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

To contribute, have a look at `Contributing <./CONTRIBUTING.rst>`__

## License
SpaceWise is released under the [Apache 2.0](https://github.com/expertailab/spacewise/blob/main/LICENSE) license

![](https://www.expert.ai/wp-content/uploads/2020/09/favicon-1.png) Expert.ai
-----------------------------

At [Expert.ai](https://expert.ai) we turn language into data so humans can make better
decisions. 


