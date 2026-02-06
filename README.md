# 🚀 MedAraBench: Large-scale Arabic Medical Question Answering Dataset and Benchmark
## Overview
Arabic remains one of the most underrepresented languages in natural language processing research, particularly in medical applications, due to the limited availability of open-source data and benchmarks. The lack of resources hinders efforts to evaluate and advance the multilingual capabilities of Large Language Models (LLMs). **MedAraBench** introduces a large-scale dataset consisting of Arabic multiple-choice question-answer pairs across 19 medical specialties and 5 difficulty levels.

The dataset was manually constructed by manually digitizing a large repository of academic materials created by medical professionals in the Arabic-speaking region. We then conducted extensive preprocessing and split the dataset into training and test sets to support future research efforts in the area. To assess the quality of the data, we adopted two frameworks, namely expert human evaluation and LLM-as-a-judge.

We conducted a comprehensive evaluation with eight state-of-the-art open-source and proprietary models, such as GPT-5, Gemini 2.0 Flash, and Claude 4-Sonnet. Our findings highlight the need for further domain-specific enhancements to achieve models ready for clinical deployment.

We release the dataset and evaluation scripts to broaden the diversity of medical data benchmarks, expand the scope of evaluation suites for LLMs, and enhance the multilingual capabilities of models for deployment in clinical settings.

## Data Split
The MedAraBench dataset consists of 24,883 Arabic medical question-answer pairs. The data was split at an 80-20 train-test ratio. The data splits are provided as CSV files in this repo.

## Citation
Found this work useful? Please consider citing our paper:

```bibtex
@misc{abudaoud2026medarabench,
      title={MedAraBench: Large-Scale Arabic Medical Question Answering Dataset and Benchmark}, 
      author={Mouath Abu-Daoud and Leen Kharouf and Omar El Hajj and Dana El Samad and Mariam Al-Omari and Jihad Mallat and Khaled Saleh and Nizar Habash and Farah E. Shamout},
      year={2026},
      eprint={2602.01714},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2602.01714}, 
}
