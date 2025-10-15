# Benchmarking Tabular Data in Banking and Finance

To evaluate model performance on common finance tasks such as banking, credit modeling, loan approval, asset management, and real estate, we benchmarked several tabular datasets. This section details the datasets used in our analysis, including a summary of their metadata and the resulting performance metrics.

## Interactive Notebook Tutorial
> [!TIP]
>
> Dive right in with our interactive Colab notebook! It's the best way to get a hands-on feel for TabPFN, walking you through installation, classification, and regression examples on benchmarking tabular data.
>
> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1K7tRvBsb8ZOSXY4zwiGH5C-MxCJVvrqu?usp=sharing)

## Data Description
For datasets and additional information refer to ![Dataset Documentation](datasets/1_Documentation.md)

## Results 
We did the experiments for 10 splits using KFolds strategy on 12 classification and 17 regression datasets, for which the normalized results can be found in the ![/results](results/) directory. Few intersting insights are shown below:
![Classification Results](results/classification_results/mean_normalized_roc_auc_bar.png.png)
![Regression Results](results/regression_results/regression_benchmark_main_results_barplot_r2.pdf)

**Contact:** For questions or contributions, reach out to me @ anshulg2743@gmail.com.
