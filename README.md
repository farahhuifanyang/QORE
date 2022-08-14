# QORE

This is the official repository for "[Open Relation Extraction via Query-based Span Prediction](https://easychair.org/publications/preprint_open/lLmV)" by [Huifan Yang](mailto:huifunny@bupt.edu.cn), [Da-Wei Li](mailto:daweilee@microsoft.com), [Zekun Li](mailto:lizekun@bupt.edu.cn), [Donglin	Yang](mailto:iceberg@bupt.edu.cn), [Jinsheng	Qi](mailto:qijs@bupt.edu.cn) and [Bin Wu](mailto:wubin@bupt.edu.cn). 
The [video talk](https://www.youtube.com/watch?v=luU40xu7QAg) and [slide](https://easychair.org/smart-slide/slide/VKrv#) are available.
Please cite & star this work if it is useful to you.


<!--### Citation-->


## Our work
- We propose a novel query-based open relation extractor QORE that utilizes a Transformers-based language model to derive a representation of the interaction between the arguments and context.
– We carry out extensive experiments on seven datasets covering four languages, showing that QORE models significantly outperform conventional rule-based systems and the state-of-the-art method LOREM.
– Considering the practical challenges of ORE, we investigate the zero-shot domain transferability and the few-shot learning ability of QORE. The experimental results illustrate that our models maintain high precisions when transferring or training on fewer data.


## Code & Datasets
The implementation of QORE model and the used experimental datasets have been integrated into the repo of [QuORE](https://github.com/farahhuifanyang/QuORE).
