# Di-GUI-3Bv0.0
As a GUI grounding model trained on top of Qwen2.5-VL-3B, we do a couple of things to train it at a low cost and get a decent performance:
1. collect public available grounding datasets and apply an efficient image-text joint deduplication algorithm to them.
2. use a short grouding prompt rather than a long action prompt, and set the training max resolution to a low number.
3. manually collect all sorts of icons from internet and synthesize the grounding data from them.
4. use lora and unfreeze the ViT during training.
