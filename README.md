# LLM/VLM Research RoadMap

<br>

```
[Pre-Transformer Background]
   ├─ RNN/LSTM
   ├─ Word2Vec (2013) 
   ├─ RNN/LSTM With Dropout (2014)
   ├─ Seq2Seq (2014)
   ├─ Bahdanau Attention (2015)
   └─ ConvS2S (2017)



[Transformer & Expansions]
   └─ Transformer (2017)
        ├─ [LLM Branch]
        │     ├─ GPT-1 (2018) → GPT-2 (2019) → GPT-3 (2020)
        │     │     └─ InstructGPT (2022, RLHF) → GPT-4 (2023)
        │     ├─ BERT (2019) → RoBERTa (2019) → ALBERT (2019) → XLNet (2019)
        │     ├─ T5 (2019)
        │     ├─ LLaMA (2023) → Q-LoRA (2023)
        │     └─ Scaling Laws (2020), Self-Instruct (2022), Constitutional AI (2023)
        │
        ├─ [Efficient Transformer Branch]
        │     ├─ Sparse Transformer (2019)
        │     ├─ Reformer (2020), Linformer (2020)
        │     ├─ Performer (2021)
        │     ├─ Longformer (2020), BigBird (2020)
        │     ├─ FlashAttention (2022)
        │     └─ Hyena (2023), RWKV (2023)
        │
        └─ [Vision Transformer Branch]
              ├─ ViT (2020) → DeiT (2020)
              ├─ Swin Transformer (2021)
              ├─ BEiT (2021)
              └─ MAE (2021), EVA (2023)



[Multimodal Extensions]
   ├─ [Early VLM]
   │     ├─ Show & Tell (2015) 
   │     ├─ Show, Attend & Tell (2015)
   │     ├─ ViLBERT (2019)
   │     └─ LXMERT (2019)
   │
   ├─ [CLIP & Successors]
   │     ├─ CLIP (2021)
   │     ├─ ALIGN (2021)
   │     ├─ BLIP (2022) → BLIP-2 (2023)
   │     └─ EVA-CLIP (2024)
   │
   └─ [Modern VLM]
         ├─ Flamingo (2022)
         ├─ PaLI (2022, Google)
         ├─ Kosmos-1 (2023, Microsoft)
         ├─ GPT-4V (2023, OpenAI)
         ├─ Gemini 1.5 (2024)
         ├─ MM1 (2024, Meta)
         └─ Video-LLaMA (2023)
```

<br>

_Will be continuously updated_

<br>

## Pre-Transformer Background

<br>

|Title|Remark|Publisher|Year|
|:---:|:---:|:---:|:---:|
|[Finding Structure in Time](https://cktrace.tistory.com/65)|SRN(RNN)|Cognitive Science|1990|
|[Long Short-Term Memory](https://cktrace.tistory.com/64)|LSTM|MIT Press|1997|
|[Distributed Representations of Words and Phrases and their Compositionality](https://cktrace.tistory.com/67)|Word2Vec(Skip-gram, CBOW)|ANIPS|2013|
|[Recurrent Neural Network Regularization](https://cktrace.tistory.com/66)|RNN/LSTM with Dropout|arXiv|2014|
|[Sequence to Sequence Learning with Neural Networks](https://cktrace.tistory.com/68)|Seq2Seq|NIPS|2014|
