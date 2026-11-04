# Hi, I'm Khursani

Multimodal ML researcher — speech, text, and vision. I lead the AI research team at [Revolab](https://www.revolab.ai/), building ASR and TTS for Malaysian speech: code-switching, noisy telephony, models fast enough for real conversations.

I run autonomous experimentation systems on top of that — agent loops that form hypotheses, run GPU experiments, and keep honest ledgers of wins and losses. I also ship production AI systems that operate themselves.

## Selected work

### Speech — training, evaluation, and shipping

- I lead Revolab's ASR and TTS research for Malaysian language. Team write-ups I authored or supervised:
  - [Malaysian ASR benchmark](https://www.revolab.ai/blogs/malaysian-asr-benchmark-dataset/) — 12 domains, 1,899 samples
  - [Failure modes in autoregressive TTS](https://www.revolab.ai/blogs/autoregressive-tts-failure-modes/) — why Orpheus 3B repeats or skips speech, down to attention patterns
  - [Building ASR for Malaysia](https://www.revolab.ai/blogs/how-we-built-asr-for-malaysia/) — code-switching, telephony audio, real-world evaluation
- [faster-enhancer-py](https://github.com/khursani8/faster-enhancer-py) — Python bindings to a C engine for streaming 48 kHz int8 speech enhancement, bit-identical to the original

### Vision and multimodal

- [RSNA Knee postmortem](https://blog.khursani.dev/the-competition-i-never-looked-at/) — I pointed an autonomous loop at an 1,638-team medical imaging competition and never opened the data. 30+ submissions, 0.958 public / 0.942 private, and an honest postmortem of what the loop could not see: label quality, teacher design, and why 1,322 teams landed in one identical leaderboard block.
- [CLIP-pytorch](https://github.com/khursani8/CLIP-pytorch) — non-JIT replication of OpenAI's CLIP
- [Splatshop](https://github.com/khursani8/Splatshop) — editing gaussian splatting models

### Autonomous experimentation

- kancil + rumpun — my experiment-management loop and GPU agent farm: hypothesis registration, kill-fast lanes, pre-registered submission bands, loss ledgers. Used across the RSNA campaign and production incidents alike.
- The same discipline runs my production systems: [semak.khursani.dev](https://semak.khursani.dev) — Malaysian transit disruptions from real rider reports on Threads, captured by an always-on browser pipeline my twin operates. [I wrote about the week it went silently broken](https://blog.khursani.dev/the-browser-that-kept-dying/), and what six root-cause fixes looked like.

### Open evaluation and Malay NLP

- [BFCL-Malay](https://huggingface.co/datasets/khursani8/bfcl-ms) — Malay adaptation of the BFCL function-calling benchmark
- [synthpre-557m](https://huggingface.co/khursani8/synthpre-557m) — Malay language-model pretraining run, checkpoint and notes
- [sev-oss](https://github.com/khursani8/sev-oss) — a System One decision stack for Malaysian language: one model, many questions, reproducible benchmarks
- [teach-aws-oss](https://github.com/khursani8/teach-aws-oss) — open experiment record: LoRA finetuning Qwen3.5-2B for Malay AWS QA, failures included

## Contact

[inbox@khursani.dev](mailto:inbox@khursani.dev) · [Hugging Face](https://huggingface.co/khursani8) · [Kaggle](https://www.kaggle.com/khursani8) · [Blog](https://blog.khursani.dev)
