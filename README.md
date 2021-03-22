# Language models comparison

### Zero-shot results in benchmarks

| Model       | Size | Creator    | Lambada ACC. | Lambada PPL. | Wikitext-103 PPL. | Public  |
| ----------- | ---- | ---------- | ------------ | ------------ | ----------------- | ------- |
| GPT-2       | 117M | OpenAI     | 45.99        | 35.13        | 37.50             | **Yes** |
| GPT-2       | 345M | OpenAI     | 55.48        | 15.60        | 26.37             | **Yes** |
| Megatron-LM | 345M | NVIDIA     | 46.26        |              | 19.22             | **Yes** |
| GPT-2       | 762M | OpenAI     | 60.12        | 10.87        | 22.05             | **Yes** |
| GPT-3       | 1.3B | OpenAI     | 63.6         | 5.44         |                   | No      |
| GPT-neo     | 1.3B | EleutherAI | 64.73        | 5.04         | 13.10             | **Yes** |
| GPT-2       | 1.5B | OpenAI     | 63.24        | 8.63         | 17.48             | **Yes** |
| Megatron-LM | 2.5B | NVIDIA     | 61.52        |              | 12.68             | No      |
| GPT-3       | 2.7B | OpenAI     | 67.1         | 4.60         |                   | No      |
| GPT-neo     | 2.7B | EleutherAI | 68.83        | 4.137        | 11.39             | **Yes** |
| GPT-3       | 6.7B | OpenAI     | 70.3         | 4.00         |                   | No      |
| Megatron-LM | 8.3B | NVIDIA     | 66.51        |              | 10.81             | No      |
| Megatron-LM | 11B  | Facebook   |              |              | 10.54             | **Yes** |
| GPT-3       | 13B  | OpenAI     | 72.5         | 3.56         |                   | No      |
| Turing-NLG  | 17B  | Microsoft  | 67.98        |              | 10.21             | No      |
| GPT-3       | 175B | OpenAI     | 76.2         | 3.00         |                   | No      |
