# NLP Project - BigOBench Dataset

### The Group
* [Donato Lepore](https://github.com/Donato23)
* [Chiara Thien Thao Nguyen Ba](https://github.com/chiaranb)
* [Flavia Nicotri](https://github.com/flanico)
* [Julia Motta Coelho de Cerqueira Paes](https://github.com/julia-mp)
* [Sofia Perini](https://github.com/SofiaPerini)

## Description

The goal of this project is the in-depth analysis of the **BigOBench** dataset. The project is divided into three main phases:
1.  **Exploratory Dataset Analysis**: Various Natural Language Processing techniques are applied to analyze the problem descriptions and their corresponding Python solutions to understand their structure and correlations.
2.  **Code Generation**: Fine-tuning experiments are conducted on several pre-trained models with the goal of automatically generating Python code from the textual description of the problem.
3.  **Complexity Classification**: The CodeBERT model is fine-tuned to train a classifier capable of predicting the time and space complexity labels associated with each solution.

## Dataset

The project uses the **BigOBench** dataset, which contains 3,105 programming problems and 1,190,250 Python solutions. The main files analyzed are:

* `problem_and_human_solutions_list.jsonl`: Contains the problem descriptions and solutions.
* `complexity_labels_light.jsonl`: Includes the time and space complexity labels for each solution.

## Project Structure

The entire project is contained within the Jupyter Notebook file `Project.ipynb`. To analyze specific parts of the code, you can look at `sections` folder

## How to Run the Project

To run the notebook, you need to have the following Python libraries installed:

* `huggingface_hub`
* `pandas`
* `tqdm`
* `matplotlib`
* `seaborn`
* `wordcloud`
* `nltk`
* `scikit-learn`
* `gensim`
* `spacy`
* `plotly`

You can install the dependencies via pip:
```bash
pip install huggingface_hub pandas tqdm matplotlib seaborn wordcloud nltk scikit-learn gensim spacy plotly

