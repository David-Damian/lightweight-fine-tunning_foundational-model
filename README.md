# Lightweight fine-tunning to foundational-model DeBERTaV3

Lightweight fine tunning to DeBERTaV3 using lmsys / toxic-chat  dataset

* **PEFT technique:** LoRA
* **Model:** `DeBERTa` improves the BERT and RoBERTa models using disentangled attention and enhanced mask decoder. With those two improvements, DeBERTa out perform RoBERTa on a majority of NLU tasks with 80GB training data.

More info at : https://huggingface.co/microsoft/deberta-v3-base

* **Evaluation approach:** Measure the log loss function

# Data
I used the `lmsys/toxic-chat` dataset to fine tune the model.

This dataset contains toxicity annotations on 10K user prompts collected from the Vicuna online demo.

# Repository structure

```
.
├── deberta-v3-base-lora/                   # Data used in the project.
├── notebooks/              # Python notebooks with solution development
├── README.md               # Project description
├── environments.yml        # YAML file that defines the environment and dependencies of the project 

```

