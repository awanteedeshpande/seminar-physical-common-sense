# seminar-physical-common-sense
Research and survey on Physical Common Sense for Seminar at Saarland University (WS 2020/21)

The following repository contains the work done as part of the Seminar on "Common Sense Knowledge Extraction and Curation (Winter Semester 2020/21)" at the Saarland University, Saarbr�cken. 
The topic of research is <b>Physical Common Sense</b>.

The contents of this repository are as follows:
<br/>
1) <br/>
[Report: Physical Common Sense](CSK_Seminar_Physical_Common_Sense.pdf) <br/>
Abstract:<br/>
When asked a simple question like �Can a baby lift a mountain?� it is immediately obvious to humans that the answer is �No�. It involves an implicit reasoning in our minds with respect to i) the sizes of a baby and a mountain, ii) the weights of a baby and a mountain, iii) the knowledge of what entities are animate, and iv) knowing that when <i>[size(entity1),weight(entity1)]<< [size(entity2),weight(entity2)]</i>, <i>entity1</i> cannot lift <i>entity2</i>. While it is very easy for humans to formulate a logical thinking process to address such questions, this common sense understanding is not easily learned by natural language models. Modeling Physical Common Sense is one of the underlying challenges for today�s Natural Language Processing and Natural Language Understanding systems. A primary reason for this is that the physical knowledge of the world is learned by humans through observation and intuition via various textual, visual, auditory and tactile stimuli. Most NLP models just learn the surface pattern relations between the input and output texts and therefore have no idea about the actual semantics of the representations. This lack of latent knowledge results in poor performanceof language models despite the superior architecture, abundance of training data, and plenty of available processing power. In this report, we give a brief overview of Physical Common Sense and present the problem of representation and learning it in NLP models. We acquaint the reader with the motivation and semantics for Physical Common Sense Reasoning. We also delve into the the research done by two prominent works in modelling Physical Common Sense. We further survey other areas of research that comprise data representation, extraction, and model architecture for this task. Lastly, we present our own evaluation and discussion of the work studied and put forth the challenges and scope of researching Physical Common Sense in Natural Language Processing. <br/> <br/>
2)<br/>
[Notebook implementation](CSK_Seminar_Forbes_2019_Implementation.ipynb): Steps to reproduce the results of the paper<br/>
**[Do Neural Language Representations Learn Physical Commonsense?](https://arxiv.org/abs/1908.02899)** <br />
For an overview of this academic publication and project, please see the [project webpage](https://mbforbes.github.io/physical-commonsense/). <br/>
The steps mentioned in the repository have been implemented in a Google Colab Notebook in a GPU runtime. <br/><br/>
3)<br/>
[Data folder](physical-commonsense/data): The contents of this folder can also be obtained by running the Jupyter Notebook. However, it has been explicitly kept to document the results obtained by reproducing the code in the main repository. It contains the sentences generated for training, and graphs and results obtained by the runs over different datasets like GloVe, ELMo, BERT etc.