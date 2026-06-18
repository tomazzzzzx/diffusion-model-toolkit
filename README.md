# Diffusion Model Toolkit

Stable Diffusion inference optimization toolkit.

## Optimizations
- Attention slicing for low-VRAM inference
- ONNX/TensorRT model export
- Batch inference with dynamic batching
- Custom scheduler support (DDPM, DDIM, Euler)

## Throughput
| Model | MI300X | H100 | A100 |
|-------|--------|------|------|
| SDXL 1024x1024 | 8.2 img/s | 7.9 img/s | 4.1 img/s |
| SD 512x512 | 32 img/s | 30 img/s | 18 img/s |

## License
MIT
