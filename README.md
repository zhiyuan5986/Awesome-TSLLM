PromptCast: A New Prompt-based Learning Paradigm for Time Series Forecasting. ArXiv 2022/09/22, TKDE 2023. [[paper]](https://arxiv.org/abs/2210.08964)[[code]](https://github.com/HaoUNSW/PISA)

One Fits All: Power General Time Series Analysis by Pretrained LM. ArXiv 2023/02/23, NeurIPS 2023. [[paper]](https://arxiv.org/abs/2302.11939)[[code]](https://github.com/DAMO-DI-ML/NeurIPS2023-One-Fits-All)
- The main challenge that blocks the development of pre-trained model for time series analysis is the lack of a large amount of data for training. This paper proposes to **retrain positional embedding and layer normalization layers of pre-trained transformer models while fine-tuning**. The results show that pre-trained models on natural language or images can lead to a comparable or state-of-the-art performance in all main time series analysis tasks.

Time-LLM: Time Series Forecasting by Reprogramming Large Language Models. ArXiv 2023/10/03, ICLR 2024. [[paper]](https://openreview.net/forum?id=Unb5CVPtae)[[code]](https://github.com/KimMeen/Time-LLM)
- This paper proposes to reprogram the input time series with text prototypes before feeding it into the frozen LLMs. What's more, to augment the LLM’s ability to reason with time series data, they propose Prompt-as-Prefix (PaP), which enriches the input context and directs the transformation of reprogrammed input patches.

## Other Methods about TS.
TimesNet: Temporal 2D-Variation Modeling for General Time Series Analysis. ArXiv 2022/10/05, ICLR2023. [[paper]](https://openreview.net/forum?id=ju_Uqw384Oq)[[code]](https://github.com/thuml/Time-Series-Library/blob/main/models/TimesNet.py)
- This paper uses a CNN-based model for **general time series analysis**. It is the main baseline of "One Fits All", ICLR 2024.
