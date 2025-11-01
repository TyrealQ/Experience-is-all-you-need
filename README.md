# Experience Is All You Need: A large Language Model Application of Fine-Tuned GPT-3.5 and RoBERTa for Aspect-Based Sentiment Analysis of College Football Stadium Reviews

Thanks for your interest! This repository contains the datasets, code, and fine-tuning materials associated with the paper *"[Experience Is All You Need: A large Language Model Application of Fine-Tuned GPT-3.5 and RoBERTa for Aspect-Based Sentiment Analysis of College Football Stadium Reviews](https://doi.org/10.1080/14413523.2024.2386467)."*

[Listen to the paper podcast on YouTube](https://youtu.be/TCzltLSmOiM)

## Dataset and Code Descriptions  

| File/Folder Name        | Description                                                                                              |
| ----------------------- | -------------------------------------------------------------------------------------------------------- |
| `Train_AE`           | Fine-tuning dataset for GPT-3.5 to extract aspects (AE).                                                 |
| `Train_CC`           | Fine-tuning dataset for GPT-3.5 to classify aspects (CC).                                                |
| `Test_all_variables` | Comprehensive testing dataset containing review texts, metadata, and all statistical analysis variables. |
| `Test_analysis`      | Testing dataset for statistical analysis.                                                                |
| `RoBERTa_eval_data`     | Evaluation dataset extracted from the training data for model assessment.                                |
| `Code_SMR`              | Python code executed on Google Colab for performing all study analyses.                                  |


## Usage

1. Clone the repository.  
2. Explore the `Train_AE` and `Train_CC` files to replicate or adapt fine-tuning for GPT-3.5.
3. Use the `Test_all_variables` and `Test_analysis` datasets to reproduce the quantitative and qualitative analyses.
4. Run the notebook(s) in `Code_SMR` to reproduce the full analytical pipeline.
5. Use `RoBERTa_eval_data` to evaluate the RoBERTa model performance.

These resources are designed to provide transparency, replicability, and adaptability for future research in sports consumer experience, large-language-model applications, and sentiment analysis.

## Citation

If you use this repository or build upon this work, please cite the associated paper:

```bibtex
@article{qian2025experience,
  title={Experience is all you need: A large language model application of fine-tuned GPT-3.5 and RoBERTa for aspect-based sentiment analysis of college football stadium reviews},
  author={Qian, Tyreal Yizhou and Li, Weizhe and Gong, Hua and Seifried, Chad and Xu, Chenglong},
  journal={Sport Management Review},
  volume={28},
  number={1},
  pages={1-25},
  year={2025},
  doi={10.1080/14413523.2024.2386467}
}
