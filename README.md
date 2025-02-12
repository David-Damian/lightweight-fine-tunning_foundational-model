# lightweight-fine-tunning_foundational-model
Lightweight fine tunning to DeBERTaV3 using lmsys / toxic-chat  dataset

* **PEFT technique:** LoRA
* **Model:** `DeBERTa` improves the BERT and RoBERTa models using disentangled attention and enhanced mask decoder. With those two improvements, DeBERTa out perform RoBERTa on a majority of NLU tasks with 80GB training data.

More info at : https://huggingface.co/microsoft/deberta-v3-base

* **Evaluation approach:** Measure the log loss function
* **Fine-tuning dataset:** `lmsys/toxic-chat` -> This dataset contains toxicity annotations on 10K user prompts collected from the Vicuna online demo.
