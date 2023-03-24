# FinSim_Financial_Hypernym_detection
Codes and models to extract hypernyms of Financial Terms

You can get the models and their weights from Hugging Face:<br>
* LIPI (prepared by fine-tuning FinBERT \cite{chopra-ghosh-2021-term} ): https://huggingface.co/sohomghosh/LIPI_FinSim3_Hypernym (Note: This model may not perfectly replicate the numbers mentioned in the paper as unlike the original one it has been trained with lower batches sizes for fewer epochs) <br>
* FinISH:  https://huggingface.co/yseop/roberta-base-finance-hypernym-identification <br>

```bibtex
@inproceedings{chopra-ghosh-2021-term,
    title = "Term Expansion and {F}in{BERT} fine-tuning for Hypernym and Synonym Ranking of Financial Terms",
    author = "Chopra, Ankush  and
      Ghosh, Sohom",
    booktitle = "Proceedings of the Third Workshop on Financial Technology and Natural Language Processing (FinNLP@IJCAI 2021)",
    month = "Aug ",
    year = "2021",
    address = "Online",
    publisher = "-",
    url = "https://aclanthology.org/2021.finnlp-1.8",
    pages = "46--51",
}
```

```bibtex
@misc{ghosh2023learning,
      title={Learning Semantic Text Similarity to rank Hypernyms of Financial Terms}, 
      author={Sohom Ghosh and Ankush Chopra and Sudip Kumar Naskar},
      year={2023},
      eprint={2303.13475},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
