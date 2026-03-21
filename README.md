Awesome—let’s build a Google Colab–ready “foundation first” program for the text-generation task using the GPT‑2 model (Hugging Face Transformers). We’ll keep it crisp, runnable, and explain the key knobs you called out:

Input → AI → Output
We’ll implement:
✅ text_analyzer(text) → sends text into AI
✅ max_new_tokens=80 → limit output size
✅ min_new_tokens=20 → ensure minimum output size
✅ do_sample=False → more stable / less random
✅ do_sample=True + temperature → more human-like (when sampling is enabled)


🔎 Notes
GPT‑2 repo name on Hugging Face is gpt2 (aka openai-community/gpt2). “Words ≠ tokens”: tokens include punctuation, spaces, and subwords.
