# LLM Papers We Recommend to Read

The past several years has marked the steady rise of large language models (LLMs), largely driven by advancements in computational power, data availability, and algorithmic innovation. LLMs have profoundly shaped the research landscape, introducing new methodologies and paradigms that challenge traditional approaches.

We have also expanded our research interests to the field of LLMs. Here are some research papers related to LLMs. We highly recommend beginners to read and thoroughly understand these papers.

:smile: **We welcome and value any contributions.**

## Basic Architectures of LLMs

| Title                                                        | Link                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| Sequence to Sequence Learning with Neural Networks           | [[paper]](https://arxiv.org/abs/1409.3215)                   |
| Transformer: Attention Is All You Need                       | [[paper]](http://arxiv.org/abs/1706.03762)                   |
| BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding | [[paper]](https://arxiv.org/abs/1810.04805)                  |
| GPT: Improving Language Understanding by Generative Pre-Training | [[paper]](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf) |
| GPT2: Language Models are Unsupervised Multitask Learners    | [[paper]](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) |
| GPT3: Language Models are Few-Shot Learners                  | [[paper]](https://arxiv.org/abs/2005.14165)                  |
| GPT3.5: Fine-Tuning Language Models from Human Preferences   | [[paper]](https://arxiv.org/abs/1909.08593)                  |
| LLaMA: Open and Efficient Foundation Language Models         | [[paper]](http://arxiv.org/abs/2302.13971)                   |
| Llama 2: Open Foundation and Fine-Tuned Chat Models          | [[paper]](http://arxiv.org/abs/2307.09288)                   |


### Multimodal Large Language Models

| Title                                                        | Link                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| Efficient Multimodal Large Language Models: A Survey           | [[paper]](http://arxiv.org/abs/2405.10739)                   |
| CLIP: Learning Transferable Visual Models From Natural Language Supervision | [[paper]](https://arxiv.org/abs/2103.00020)                  |

## Parallelism Training System

| Title                                                        | Link                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| Megatron-LM: Training Multi-Billion Parameter Language Models Using Model Parallelism | [[paper]](http://arxiv.org/abs/1909.08053)                   |
| ZeRO: Memory Optimizations Toward Training Trillion Parameter Models | [[paper]](http://arxiv.org/abs/1910.02054)                   |
| ZeRO-Infinity: Breaking the GPU Memory Wall for Extreme Scale Deep Learning | [[paper]](http://arxiv.org/abs/2104.07857)                   |
| ZeRO-Offload: Democratizing Billion-Scale Model Training     | [[paper]](https://www.usenix.org/conference/atc21/presentation/ren-jie) |
| PipeDream: generalized pipeline parallelism for DNN training | [[paper]](https://arxiv.org/abs/1806.03377)                  |
| GPipe: Efficient Training of Giant Neural Networks using Pipeline Parallelism | [[paper]](http://arxiv.org/abs/1811.06965)                   |
| TeraPipe: Token-Level Pipeline Parallelism for Training Large-Scale Language Models | [[paper]](http://arxiv.org/abs/2102.07988)                   |
| GShard: Scaling Giant Models with Conditional Computation and Automatic Sharding | [[paper]](http://arxiv.org/abs/2006.16668)                   |
| PanGu-$\Sigma$: Towards Trillion Parameter Language Model with Sparse Heterogeneous Computing | [[paper]](http://arxiv.org/abs/2303.10845)                   |
| DeepSpeed-MoE: Advancing Mixture-of-Experts Inference and Training to Power Next-Generation AI Scale | [[paper]](https://proceedings.mlr.press/v162/rajbhandari22a.html) |
| Accelerating Distributed MoE Training and Inference with Lina | [[paper]](https://www.usenix.org/conference/atc23/presentation/li-jiamin) |
| Galvatron: Efficient Transformer Training over Multiple GPUs Using Automatic Parallelism | [[paper]](http://arxiv.org/abs/2211.13878)                   |
| Alpa: Automating Inter- and {Intra-Operator} Parallelism for Distributed Deep Learning | [[paper]](https://www.usenix.org/conference/osdi22/presentation/zheng-lianmin) |

## LLM Serving System

I think the work on LLM serving can be categorized into the following fields: *systematic optimization* (e.g., vLLM), *scheduling optimization* (e.g., DistServe, Llumnix), *offloading* (e.g., FlexGen), *prefix-sharing*, *KV cache compression/eviction/selection*, and *speculative decoding*. 

I will conduct actual categorization in the future.

| Title                                                        | Link                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| Towards Efficient Generative Large Language Model Serving: A Survey from Algorithms to Systems | [[paper]](http://arxiv.org/abs/2312.15234)                   |
| FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness | [[paper]](https://arxiv.org/abs/2205.14135)                  |
| Efficiently Scaling Transformer Inference                    | [[paper]](http://arxiv.org/abs/2211.05102)                   |
| vLLM: Efficient Memory Management for Large Language Model Serving with PagedAttention | [[paper]](http://arxiv.org/abs/2309.06180)                   |
| DeepSpeed-Inference: Enabling Efficient Inference of Transformer Models at Unprecedented Scale | [[paper]](https://arxiv.org/abs/2207.00032)                  |
| Orca: A Distributed Serving System for Transformer-Based Generative Models | [[paper]](https://www.usenix.org/conference/osdi22/presentation/yu) |
| FlexGen: High-Throughput Generative Inference of Large Language Models with a Single GPU | [[paper]](http://arxiv.org/abs/2303.06865)                   |
| S$^{3}$: Increasing GPU Utilization during Generative Inference for Higher Throughput | [[paper]](http://arxiv.org/abs/2306.06000)                   |
| Splitwise: Efficient generative LLM inference using phase splitting | [[paper]](http://arxiv.org/abs/2311.18677)                   |
| SpecInfer: Accelerating Generative Large Language Model Serving with Speculative Inference and Token Tree Verification | [[paper]](https://arxiv.org/abs/2305.09781)                  |
| Petals: Collaborative Inference and Fine-tuning of Large Models | [[paper]](https://aclanthology.org/2023.acl-demo.54)         |
| PowerInfer: Fast Large Language Model Serving with a Consumer-grade GPU | [[paper]](http://arxiv.org/abs/2312.12456)                   |
| DistServe: Disaggregating Prefill and Decoding for Goodput-optimized Large Language Model Serving | [[paper]](http://arxiv.org/abs/2401.09670)                   |
| LoongServe: Efficiently Serving Long-context Large Language Models with Elastic Sequence Parallelism | [[paper]](http://arxiv.org/abs/2404.09526)                   |
| Vidur: A Large-Scale Simulation Framework For LLM Inference  | [[paper]](http://arxiv.org/abs/2405.05465)                   |
| Lean Attention: Hardware-Aware Scalable Attention Mechanism for the Decode-Phase of Transformers | [[paper]](http://arxiv.org/abs/2405.10480)                   |
| AlpaServe: Statistical Multiplexing with Model Parallelism for Deep Learning Serving | [[paper]](http://arxiv.org/abs/2302.11665)                   |
| SARATHI: Efficient LLM Inference by Piggybacking Decodes with Chunked Prefills | [[paper]](http://arxiv.org/abs/2308.16369)                   |
| Taming Throughput-Latency Tradeoff in LLM Inference with Sarathi-Serve | [[paper]](http://arxiv.org/abs/2403.02310)                   |
| Llumnix: Dynamic Scheduling for Large Language Model Serving | [[paper]](http://arxiv.org/abs/2406.03243)                   |
| Mooncake: A KVCache-centric Disaggregated Architecture for LLM Serving | [[paper]](http://arxiv.org/abs/2407.00079)                   |
| InfiniGen: Efficient Generative Inference of Large Language Models with Dynamic KV Cache Management | [[paper]](http://arxiv.org/abs/2406.19707)                   |
| ServerlessLLM: Low-Latency Serverless Inference for Large Language Models | [[paper]](https://www.usenix.org/conference/osdi24/presentation/fu) |
| Is the GPU Half-Empty or Half-Full? Practical Scheduling Techniques for LLMs | [[paper]](http://arxiv.org/abs/2410.17840)                   |
| NEO: Saving GPU Memory Crisis with CPU Offloading for Online LLM Inference | [[paper]](http://arxiv.org/abs/2411.01142)                   |
| EcoServe: Maximizing Multi-Resource Utilization with SLO Guarantees in LLM Serving | [[paper]](http://arxiv.org/abs/2411.06364)                   |

### Serving LLMs with Multiple LoRAs

| Title                                                        | Link                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| PetS: A Unified Framework for Parameter-Efficient Transformers Serving | [[paper]](https://www.usenix.org/conference/atc22/presentation/zhou-zhe) |
| Punica: Multi-Tenant LoRA Serving                            | [[paper]](http://arxiv.org/abs/2310.18547)                   |
| S-LoRA: Serving Thousands of Concurrent LoRA Adapters        | [[paper]](http://arxiv.org/abs/2311.03285)                   |
| dLoRA: Dynamically Orchestrating Requests and Adapters for LoRA LLM Serving | [[paper]](https://www.usenix.org/conference/osdi24/presentation/wu-bingyang) |

## Parameter-Efficient Fine-Tuning (PEFT)

| Title                                                        | Link                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| Delta Tuning: A Comprehensive Study of Parameter Efficient Methods for Pre-trained Language Models | [[paper]](http://arxiv.org/abs/2203.06904)                   |
| Parameter-Efficient Transfer Learning for NLP                | [[paper]](https://proceedings.mlr.press/v97/houlsby19a.html) |
| Prefix-Tuning: Optimizing Continuous Prompts for Generation  | [[paper]](http://arxiv.org/abs/2101.00190)                   |
| LoRA: Low-Rank Adaptation of Large Language Models           | [[paper]](http://arxiv.org/abs/2106.09685)                   |
| Towards a Unified View of Parameter-Efficient Transfer Learning | [[paper]](http://arxiv.org/abs/2110.04366)                   |
| Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning | [[paper]](http://arxiv.org/abs/2303.10512)                   |
| When Scaling Meets LLM Finetuning: The Effect of Data, Model and Finetuning Method | [[paper]](http://arxiv.org/abs/2402.17193)                   |
| Unleashing the Power of Task-Specific Directions in Parameter Efficient Fine-tuning | [[paper]](http://arxiv.org/abs/2409.01035)                   |
| DoRA: Weight-Decomposed Low-Rank Adaptation                  | [[paper]](http://arxiv.org/abs/2402.09353)                   |
| GaLore: Memory-Efficient LLM Training by Gradient Low-Rank Projection | [[paper]](http://arxiv.org/abs/2403.03507)                   |

## Compression (Quantization, Sparsity)

| Title                                                        | Link                                        |
| ------------------------------------------------------------ | ------------------------------------------- |
| LLM.int8(): 8-bit Matrix Multiplication for Transformers at Scale | [[paper]](http://arxiv.org/abs/2208.07339)  |
| GPTQ: Accurate Post-Training Quantization for Generative Pre-trained Transformers | [[paper]](https://arxiv.org/abs/2210.17323) |
| AWQ: Activation-aware Weight Quantization for LLM Compression and Acceleration | [[paper]](http://arxiv.org/abs/2306.00978)  |
| QServe: W4A8KV4 Quantization and System Co-design for Efficient LLM Serving | [[paper]](http://arxiv.org/abs/2405.04532)  |
| Deja Vu: Contextual Sparsity for Efficient LLMs at Inference Time | [[paper]](https://arxiv.org/abs/2310.17157) |
| Atom: Low-bit Quantization for Efficient and Accurate LLM Serving | [[paper]](http://arxiv.org/abs/2310.19102)  |
| QLoRA: Efficient Finetuning of Quantized LLMs                | [[paper]](http://arxiv.org/abs/2305.14314)  |

