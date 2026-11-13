# llm-agent-experiments

Experiments with running open-source LLMs (Qwen, DeepSeek, Gemma, GLM) locally with llama.cpp and in the cloud via OpenAI-compatible APIs, and building lightweight AI agents that offload tasks to these models.

## Plans
- Benchmark small quantized models (GGUF, Q4_K_M) on CPU vs. cloud GPU inference
- Lightweight tool-calling agent that routes tasks to different models
- Compare latency and quality of open models on AMD Instinct GPUs
