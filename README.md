# TabReformer
*Bidirectional Representation Model for Erroneous Data Detection*

Error detection is a crucial preliminary phase in any data analytics pipeline. Existing error detection techniques are typically targeted to detect certain types of errors. Moreover, most of these detection models either require user-defined rules or ample hand-labeled training examples. Therefore, we present Reformer, which is a model that learns bidirectional encoder representations for tabular data. The proposed model consists of two main phases. In the first phase, Reformer follows encoder architecture with multi self-attention layers to model the dependencies between cells and capture tuple-level representations. Also, the model utilizes the Gaussian Error Linear Unit activation function with the Masked Data Model objective to achieve deeper probabilistic understanding. Then, in the second phase, the model parameters are fine-tuned with the task of erroneous data detection. 

## Installation

To install TabReformer, you can clone the Git repository and run:

    pip install -e .

within it.
