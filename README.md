# ComfyUI-SmartModelLoaders-MXD

Smart, unified model loaders for ComfyUI that support both standard `.safetensors` and quantized `.gguf` formats — no switching nodes required.

Includes flexible UNET and CLIP loaders that work across models like SDXL, SD3, Flux, and more.

---

## ✅ Features

- 🧠 Unified loaders for `.safetensors` and `.gguf` formats
- 🔀 Drop-in replacements for standard UNET and CLIP nodes
- 💪 Supports single, dual, triple, and quad CLIP configs
- ⚙️ Internal handling of GGUF logic with `GGMLOps` and `GGUFModelPatcher`
- 🧼 Clean fallback to standard ComfyUI loading when needed

---

## 📦 Included Nodes

| Node Name                    | Purpose                                                                 |
|-----------------------------|-------------------------------------------------------------------------|
| `Smart UNET Loader MXD`     | Loads UNET from `.safetensors` or `.gguf`                               |
| `Smart CLIP Loader MXD`     | Loads a single CLIP model of any supported format                       |
| `Smart Dual CLIP Loader MXD`| Loads 2 CLIPs (ideal for SDXL, Flux, etc.)                              |
| `Smart Triple CLIP Loader MXD` | Loads 3 CLIPs (used in SD3 and similar setups)                      |
| `Smart Quad CLIP Loader MXD`   | Loads 4 CLIPs (for advanced/experimental workflows)                |

---

## 🧩 Installation

Clone directly into your ComfyUI custom nodes directory:

```bash
git clone https://github.com/YOUR_USERNAME_HERE/ComfyUI-SmartModelLoaders-MXD.git
```

Optionally, ensure gguf is installed if not already:

```bash
pip install --upgrade gguf
```

📸 Example Use
Coming soon — full workflow demos for SDXL, SD3, and Flux setups.

🙏 Attribution
This project is based on and extends:

city96/ComfyUI-GGUF
Licensed under Apache 2.0 License

Modifications, restructuring, and additional loader support by MaxedOut (2025).




