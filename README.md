# Utterance data augmentation data

This repository contains the datasets created in the paper *Zero-shot utterance data augmentation for intent classification through Large Language Models*. This paper proposes a new approach for zero-shot utterance augmentation to improve intent classification using Large Language Models.


## Datasets

The `data` folder contains three excel files related to surveillance in financial trading:

- `intents_general_paraphrases.xlsx`: 8 intent reference utterances with only general language vocabulary, alongside 150 semantically and 300 non-semantically similar utterances.
- `intents_financial_paraphrases.xlsx`: 7 intent reference utterances with financial trading surveillance vocabulary, alongside 50 semantically and 100 non-semantically similar utterances.
- `intents_general_financial_paraphrases.xlsx`: concatenation of the `intents_financial_paraphrases.xlsx` and `intents_general_paraphrases.xlsx` files. It contains both general language and financial trading surveillance vocabulary.

The `intents_general_paraphrases.xlsx` and `intents_general_financial_paraphrases.xlsx` files corresponds to the `Intents General Paraphrases` and `Intents General and Financial Paraphrases` datasets described in *Zero-shot utterance data augmentation for intent classification through Large Language Models*.


## Acknowledgments

The creation of these datasets was supported by VoxSmart Trading S.L., and grants from Madrid Autonomous Community (Ref: IND2023/TIC-28393), the Spanish Ministry of Science and Innovation, under the Knowledge Generation Projects program: XMIDAS (Ref: PID2021-122640OB-100) and Rey Juan Carlos University (Ref: C1PREDOC2020).