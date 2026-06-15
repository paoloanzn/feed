### Main Topic: AI Consistency Training

**Main Thesis:** New methods for consistency training generalize better across various threats, and the best method depends on whether the failure is caused by the input wrapper or the entire response path.

**Simple Summary:** This research introduces new ways to train AI models to be consistent and safe, ensuring they don't change their answers when faced with tricky prompts. The authors developed two new methods (MLPCT and AttCT) that check consistency at different parts of the model (internal calculations vs. attention weights). They found that depending on the type of problem (like persona attacks or frustration), some methods work much better than others. The key takeaway is that you should use methods that check the internal workings of the model when the failure is caused by the input prompt, and use other methods when the failure involves the entire response.

**The Bottom Line:** > Use methods that check the model's internal workings for prompt-related failures, and use methods that check the final output for failures that affect the entire response.

---
*Original article: https://www.lesswrong.com/posts/zLERnZYLTPGqyfpqy/two-more-methods-for-consistency-training-and-some-new-ways-1*
