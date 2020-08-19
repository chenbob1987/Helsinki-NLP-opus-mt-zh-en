---
language: 
- zh
- en
- cmn
- yue

tags:
- translation

license: apache-2.0
---

### zho-eng

* source group: Chinese 
* target group: English 
*  OPUS readme: [zho-eng](https://github.com/Helsinki-NLP/Tatoeba-Challenge/tree/master/models/zho-eng/README.md)

*  model: transformer
* source language(s): cjy_Hans cjy_Hant cmn cmn_Hans cmn_Hant gan lzh lzh_Hans nan wuu yue yue_Hans yue_Hant
* target language(s): eng
* model: transformer
* pre-processing: normalization + SentencePiece (spm32k,spm32k)
* download original weights: [opus-2020-07-17.zip](https://object.pouta.csc.fi/Tatoeba-MT-models/zho-eng/opus-2020-07-17.zip)
* test set translations: [opus-2020-07-17.test.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/zho-eng/opus-2020-07-17.test.txt)
* test set scores: [opus-2020-07-17.eval.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/zho-eng/opus-2020-07-17.eval.txt)

## Benchmarks

| testset               | BLEU  | chr-F |
|-----------------------|-------|-------|
| Tatoeba-test.zho.eng 	| 36.1 	| 0.548 |


### System Info: 
- hf_name: zho-eng

- source_languages: zho

- target_languages: eng

- opus_readme_url: https://github.com/Helsinki-NLP/Tatoeba-Challenge/tree/master/models/zho-eng/README.md

- original_repo: Tatoeba-Challenge

- tags: ['translation']

- prepro:  normalization + SentencePiece (spm32k,spm32k)

- url_model: https://object.pouta.csc.fi/Tatoeba-MT-models/zho-eng/opus-2020-07-17.zip

- url_test_set: https://object.pouta.csc.fi/Tatoeba-MT-models/zho-eng/opus-2020-07-17.test.txt

- src_alpha3: zho

- tgt_alpha3: eng

- short_pair: zh-en

- chrF2_score: 0.5479999999999999

- bleu: 36.1

- brevity_penalty: 0.948

- ref_len: 82826.0

- src_name: Chinese

- tgt_name: English

- train_date: 2020-07-17

- src_alpha2: zh

- tgt_alpha2: en

- prefer_old: False

- long_pair: zho-eng

- helsinki_git_sha: 480fcbe0ee1bf4774bcbe6226ad9f58e63f6c535

- transformers_git_sha: 46e9f53347bbe9e989f0335f98465f30886d8173

- port_machine: brutasse

- port_time: 2020-08-18-01:48