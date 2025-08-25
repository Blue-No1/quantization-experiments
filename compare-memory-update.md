# Memory Footprint Comparison (Extended Draft)

| Model | Format | Size (est.) | Speed | Accuracy |
|-------|--------|-------------|-------|----------|
| GPT-OSS-120B | FP32 | ~400 GB | slow | baseline |
| GPT-OSS-120B | FP16 | ~200 GB | medium | close |
| GPT-OSS-120B | INT8 | ~100 GB | fast | some loss |
| GPT-OSS-120B | GGUF 4bit | ~50 GB | fastest | more loss |
| Llama 3 70B | FP16 | ~140 GB | medium | close |
| Llama 3 70B | INT8 | ~70 GB | fast | some loss |
| Llama 3 70B | 4bit | ~35 GB | fastest | noticeable loss |
| Mixtral 8x7B | FP16 | ~120 GB | medium | close |
| Mixtral 8x7B | INT8 | ~60 GB | fast | some loss |
| Mixtral 8x7B | 4bit | ~30 GB | fastest | noticeable loss |
