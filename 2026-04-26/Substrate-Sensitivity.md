### Main Topic: AI Safety Implementation

**Main Thesis:** The safety and behavior of AI systems depend not only on the model itself but also on the specific ways the model is built, stored, and run on the underlying hardware.

**Simple Summary:** The article argues that what we observe about an AI's safety is affected by hidden choices made during its creation and deployment. This includes how the network is designed (like using LayerNorm), how its numbers are stored (quantization), and the physical hardware it runs on (like memory chips). These low-level choices—the "substrate"—can silently change whether the AI is safe or vulnerable to attacks. For example, a specific way weights are stored (like INT4 vs. FP16) changes how easily an attacker can break the system, and the type of memory used in the computer also affects security.

**The Bottom Line:** > To ensure true AI safety, we must look beyond the model itself and understand the full chain of implementation, from the code to the physical hardware, because these hidden choices determine the system's actual security.

---
*Original article: https://www.lesswrong.com/posts/wEfWFSBvpJwkfX3Rs/substrate-sensitivity*
