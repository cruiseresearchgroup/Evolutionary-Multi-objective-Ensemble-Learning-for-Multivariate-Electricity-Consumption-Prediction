> **If you use the resources (algorithm, code and dataset) presented in this repository, please cite our paper.**  
*The BibTeX entry is provided at the bottom of this page. 

# Evolutionary Multi-objective Ensemble Learning for Multivariate Electricity Consumption Prediction
Energy consumption prediction typically corresponds to a multivariate time series prediction task where different channels in the multivariate time series represent energy consumption data and various auxiliary data related to energy consumption such as environmental factors. It is non-trivial to resolve this task, which requires finding the most appropriate prediction model and the most useful features (extracted from
the raw data) to be used by the model. This work proposes an evolutionary multi-objective ensemble learning (EMOEL) technique which uses extreme learning machines (ELMs) as base predictors due to its highly recognized efficacy. EMOEL employs evolutionary multi-objective optimization to search for the optimal parameters of the model as well as the optimal features fed into the model subjected to two conflicting criteria, i.e., accuracy and diversity. It leads to a Pareto front com- posed of non-dominated optimal solutions where each solution depicts the number of hidden neurons in the ELM, the selected channels in the multivariate time series, the selected feature extraction methods and the selected time windows applied to the selected channels. The optimal solutions in the Pareto front stand for different end-to-end prediction models which may lead to different prediction results. To boost ultimate prediction accuracy, the models with respect to these optimal solutions are linearly combined with combination coefficients being optimized via an evolutionary algorithm. We evaluate the proposed method in comparison to some existing prediction techniques on an Australian University based dataset, which demonstrates the superiority of the proposed method. 

This repository contains resources developed within the following paper:

  Song, H., Qin, A. K., & Salim, F. D. (2018). Evolutionary Multi-objective Ensemble Learning for Multivariate Electricity Consumption Prediction. 
  In 2018 International Joint Conference on Neural Networks (IJCNN). IEEE, 2018.
  
You can find the [paper](link_to_your_github_pdf_resource_file.pdf) and [presentation](link_to_your_github_pdf_resource_file.pdf) in this repository. 

Alternative link: **TBD**

## Contents of the repository
This repository contains resources used and described in the paper.

The repository is structured as follows:
- `paper/`: Formal description of the algorithm and evaluation results
- `presentation/`: The presentation slides

## Citation
If you use the resources (code and dataset) presented in this repository, please cite (using the following BibTeX entry):
```
**TBD**
@inproceedings{song2018evolutionary,
  title={Evolutionary Multi-objective Ensemble Learning for Multivariate Electricity Consumption Prediction},
  author={Song, Hui and Qin, A. K. and Salim, Flora D.},
  booktitle={2018 International Joint Conference on Neural Networks (IJCNN)},
  pages={1--999},
  year={2018},
  organization={IEEE}
}
```
