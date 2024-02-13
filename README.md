# SpaceWise
[![Supported Python Versions](https://badgen.net/pypi/python/black)](https://www.python.org/)

SpaceWise short description

# Background
SpaceWise is the natural continaution in our efforts to bring LLM capabilities to the Space domain. Previously we have developed SpaceQA,an open-domaing extractive question answering system, that uees a  language models to identify the specific text fragment in a document collection that answers a user’s query. 

## SpaceQA 
Recently, we collaborated with ESA to streamline access to information about early designs of space missions leveraging LLM. To this end we develope the QA system [SpaceQA](https://arxiv.org/abs/2210.03422) relying on a autoencoder model. SpaceQA has successfully enabled users to access information using questions in natural language that was previously available only in lengthy feasibility studies in PDF format. 

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

SpaceWise goes a step forward and embrace the power of generative language models conversational chatbots and retrieval augmented generation to unlock new possibilities for accessing space information, benefiting both ESA staff and space enthusiasts.  

# Contribution

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

To contribute, have a look at `Contributing <./CONTRIBUTING.rst>`__

# License
SpaceWise is released under the [Apache 2.0](https://github.com/expertailab/spacewise/blob/main/LICENSE) license

![](https://www.expert.ai/wp-content/uploads/2020/09/favicon-1.png) Expert.ai
-----------------------------

At [Expert.ai](https://expert.ai) we turn language into data so humans can make better
decisions. 


