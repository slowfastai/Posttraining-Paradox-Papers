# 🤯 What Is the Post-Training Paradox?

**Post-training** refers to the process of applying techniques such as **Supervised Fine-Tuning (SFT)**, **Reinforcement Learning from Human Feedback (RLHF)**, or **Reinforcement Learning with Verifiable Rewards (RLVR)** — individually or in combination — on a pretrained base model.

When I first encountered the idea of post-training, I naturally assumed that the resulting model would surpass the base model in **all aspects of its capabilities**.
Perhaps you thought so too. But is that really the case?

`💡 “Post-training makes models nicer. But does it make them smarter?”`

Driven by this curiosity, I began investigating papers whose experimental results challenge the assumption that post-training consistently enhances a model’s capacity.
I call this phenomenon the **Post-Training Paradox**.

Broadly speaking, the Post-Training Paradox refers to cases where post-training — whether via SFT, RLHF, or RLVR — fails to improve, or even degrades, the base model’s capabilities in certain areas. Put simply, in my view, **any case where post-training fails to enhance the base model in all aspects of its capability qualifies as a post-training paradox**.

For example:
	•	A model fine-tuned via SFT on physics-domain QA data may perform better in physics, but worse on unrelated tasks.
	•	An RLVR-trained model might not gain new reasoning ability — it may simply **alter the sampling distribution** of the base model’s responses without expanding its cognitive reach.


# ❓ Why Study the Post-Training Paradox?

Not because I oppose post-training — quite the opposite.

I believe post-training is essential. Precisely because of its importance, we should strive to understand how it transforms base models at a deeper level.
After all, the models we deploy to serve humans are the ones that have undergone post-training.

`🧪 While base models are still (just barely) within the reach of human comprehension,
let’s take this moment to study them — deeply, critically, and urgently.`

# Paper list

## SFT


## RLHF


## RLVR

