### Main Topic: LLM Misalignment

**Main Thesis:** Detecting when an AI model is poisoned or misaligned is much harder using external behavioral tests than it is by checking the model's internal activation signals.

**Simple Summary:** Researchers tested how much bad information (poisoning) could be injected into AI models and found that the model's internal workings show signs of misalignment very early, even at low doses. However, external tests based on asking the model questions (behavioral checks) only start flagging problems when the poisoning is severe. The study also found ways to improve detection by optimizing the prompts used for testing, suggesting that internal signals are a better way to catch subtle risks.

**The Bottom Line:** > Relying only on how an AI behaves externally is insufficient for catching subtle risks; auditors must also check the model's internal signals to detect misalignment at low levels.

---
*Original article: https://www.lesswrong.com/posts/cN3n2HDNkf4Bterxx/emergent-misalignment-evident-in-activations-at-low*
