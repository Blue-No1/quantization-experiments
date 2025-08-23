# Memory Footprint Comparison (Draft) 
| Format | Size (GPT-OSS-120B est.) | Speed | Accuracy | 
|--------|--------------------------|-------|----------| 
| FP32 | ~400 GB | slow | baseline | 
| FP16 | ~200 GB | medium | close | 
| INT8 | ~100 GB | fast | some loss | 
| GGUF 4bit | ~50 GB | fastest | more loss |
