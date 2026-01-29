# CyrillicQA
Do LLMs possess the creativity and faculty of abstraction necessary to decipher phonetically encoded language the same way humans do?

## Datasets
This repository includes three variants of the [_TruthfulQA_ dataset](https://arxiv.org/abs/2109.07958) under ``datasets/TruthfuLQA/``:

| Script        | Description                                                  	| Path                       	|
|-------------- |--------------------------------------------------------------	|----------------------------	|
| _Latin_    	| The original English language version (stripped to MC0)      	| ``mc0_task.json``          	|
| _IPA_      	| A version converted into the [International Phonetic Alphabet](https://en.wikipedia.org/wiki/International_Phonetic_Alphabet) 	| ``mc0_task_ipa.json``      	|
| _Cyrillic_    | A version cyrillized into the Russian Cyrillic alphabet      	| ``mc0_task_cyrillic.json`` 	|

All three variants were successively generated from the original dataset published at [github.com/sylinrl/TruthfulQA](https://github.com/sylinrl/TruthfulQA/blob/main/data/mc_task.json), accessed on December 12, 2025.
The whole conversion process is documented in ``experimental_pipeline.ipynb`` and can be rerun from there.