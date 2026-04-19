### Main Topic: Model Steering

**Main Thesis:** Steering the model's internal information (hidden states vs. key-value cache) depends heavily on which data the model is allowed to remember during reasoning.

**Simple Summary:** The article investigates different ways to guide a language model (CoDI) to perform reasoning. It compares steering methods based on two types of information: hidden states (what the model is thinking) and KV cache (what the model remembers). The research found that steering the KV cache works better than steering the hidden states, and the way the model stores information (the KV cache) seems to limit how much reasoning it can perform before it forgets the details.

**The Bottom Line:** > To effectively control how a model reasons, researchers must understand exactly what information the model saves, as steering methods that rely on hidden states often fail compared to those that use the saved key-value information.

---
*Original article: https://www.lesswrong.com/posts/zcdpKZyMj2jENtRuL/latent-reasoning-sprint-4-pca-analysis-on-codi-1*
