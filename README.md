## Benjamin - LLM inference & GPU systems 🇻🇳

I make large models serve faster: attention and MoE kernels, quantized GEMMs, and the serving-engine plumbing around them. I also build and ship iOS apps on the side.

### Highlights
- **SGLang contributor** - merged work on Gemma 4, MoE and DeepSeek sparse attention:
  - [FA4 on Hopper (SM90) with head_dim 512 for Gemma 4](https://github.com/sgl-project/sglang/pull/42019)
  - [Faster w4a8 MoE for GLM-5.2 on H200](https://github.com/sgl-project/sglang/pull/38220) - up to 1.23× faster
  - [int32 offset overflow fix in the CUTLASS MoE pre-reorder](https://github.com/sgl-project/sglang/pull/35188)
  - [DSA ragged seed-index fix before MTP draft decode](https://github.com/sgl-project/sglang/pull/42565)
  - In review: [per-layer attention backends for Gemma 4](https://github.com/sgl-project/sglang/pull/44399), [FlashInfer SM90 w4a8 CUTLASS MoE](https://github.com/sgl-project/sglang/pull/40538)
- **GPU kernels** - throughput-focused C++ kernel work on AMD hardware

### Stack
C++ · CUDA · HIP · CUTLASS · Triton · Python · PyTorch · SGLang · vLLM
Swift · SwiftUI · TypeScript · React

### Open to
LLM inference / ML systems roles and collaborations.

📫 [ngoctruonggia@gmail.com](mailto:ngoctruonggia@gmail.com) · [LinkedIn](https://www.linkedin.com/in/ngoctruonggia/)
