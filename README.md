PromptCast: A New Prompt-based Learning Paradigm for Time Series Forecasting. ArXiv 2022/09/22, TKDE 2023. [[paper]](https://arxiv.org/abs/2210.08964)[[code]](https://github.com/HaoUNSW/PISA)

One Fits All: Power General Time Series Analysis by Pretrained LM. ArXiv 2023/02/23, NeurIPS 2023. [[paper]](https://arxiv.org/abs/2302.11939)[[code]](https://github.com/DAMO-DI-ML/NeurIPS2023-One-Fits-All)
- The main challenge that blocks the development of pre-trained model for time series analysis is the lack of a large amount of data for training. This paper proposes to **retrain positional embedding and layer normalization layers of pre-trained transformer models while fine-tuning**. The results show that pre-trained models on natural language or images can lead to a comparable or state-of-the-art performance in all main time series analysis tasks.

TEST: Text Prototype Aligned Embedding to Activate LLM's Ability for Time Series. ArXiv 2023/08/16. ICLR 2024. [[paper]](https://openreview.net/forum?id=Tuh4nZVb0g)[[code]](https://github.com/SCXsunchenxi/TEST)

Time-LLM: Time Series Forecasting by Reprogramming Large Language Models. ArXiv 2023/10/03, ICLR 2024. [[paper]](https://openreview.net/forum?id=Unb5CVPtae)[[code]](https://github.com/KimMeen/Time-LLM)
- This paper proposes to reprogram the input time series with text prototypes before feeding it into the frozen LLMs. What's more, to augment the LLM’s ability to reason with time series data, they propose Prompt-as-Prefix (PaP), which enriches the input context and directs the transformation of reprogrammed input patches.


## Why use LLM for TS?
In "One Fits All" (NeurIPS 2023), the authors argue that the main challenge that blocks the development of pre-trained model for time series analysis is the lack of a large amount of data for training. Unlike NLP and CV where a unified model can be used to perform different tasks, there are different approaches designed for different TS analysis task. So the authors propose to retrain positional embedding and layer normalization layers of pre-trained transformer models while fine-tuning. 
<!-- The results show that pre-trained models on natural language or images can lead to a comparable or state-of-the-art performance in all main time series analysis tasks. -->

In "Time-LLM" (ICLR 2024), the authors hold the believe that pre-trained foundation models in time series domains has been constrained by data sparsity (the amount of data is not enough). Their choice is to directly deploy a frozen pre-trained LLMs, which possess robust pattern recognition and reasoning abilities over complex sequences of tokens. They think the challenge remains in effectively aligning the modalities of time series data and natural language to leverage these capabilities.


## Other Methods about TS.
TimesNet: Temporal 2D-Variation Modeling for General Time Series Analysis. ArXiv 2022/10/05, ICLR2023. [[paper]](https://openreview.net/forum?id=ju_Uqw384Oq)[[code]](https://github.com/thuml/Time-Series-Library/blob/main/models/TimesNet.py)
- This paper uses a CNN-based model for **general time series analysis**. It is the main baseline of "One Fits All", ICLR 2024.
