# TRESPASSED: Task-oriented REference-based Synthetic ProActivity aSSEssment Dialogues

The files consist in LLM-generated task-oriented dialogues in italian, based on human references from the D-Pro Corpus (https://github.com/sofiabrenna/d-pro_corpus). The synthetic dialogues have been automatically annotated for the presence of _proactivity_.
Dialogues have been generated in three different generation modalities: with limited dialogue context, with incremental context following a human dialogue, and in one-shot modality, where the model is let free to generate the whole dialogue.

The models employed are: GPT-5-mini, Qwen3 14B, Gemma3 4B, Gemma3 27B.
The reference dialogue datset is D-Pro, with the 5 sub-corpora: Nespole, WhatsApp, Jilda, MultiWOZ, Ubuntu.
