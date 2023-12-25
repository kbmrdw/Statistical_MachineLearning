# Statistical_MachineLearning
## Title: DETECTING TOXIC COMMENTS USING MACHINE LEARNING

In this paper, we introduce our dataset for identity toxicity of Vietnamese comments on social media, extremely in game domain. To ensure the quality of the dataset, we build a detailed and clear
annotation scheme. We also use machine learning methods to build model for evaluating this dataset. All model work effectively on this dataset and they can be applied in the practical.
- **Input:** a Vietnamese comment.
- **Output:** assign as 1 if the comment is offensive, otherwise assign 0.

### [Dataset:](https://github.com/kbmrdw/Statistical_MachineLearning/blob/main/data/toxic_comment.csv)
The dataset has 3130 rows of data, which has two column : one is text and another is label. Text column contain comments that is collected from game matches. Label column is the label of data that we will predict. It includes two value : 0 and 1. 

The dataset we built is a collection of texts, and it is an unstructured data, which is why it is difficult to be approach with models without applying preprocessing methods. So in the next step, we preprocessed texts in corpus. It includes:
- Converting all letters of comments to lowercase situation.
- Removing teencode and stopwords.
- Replacing acronyms with complete words and correct spelling mistakes.
- Removing extra spaces.
- Deleting intentionally duplicated words.
- Adding cleaned comments to the data.

### Work Flow:
![](https://github.com/kbmrdw/Statistical_MachineLearning/blob/main/system.png)

***Report***: https://github.com/kbmrdw/Statistical_MachineLearning/blob/main/Nhom2_20520805_20521443.pdf

***Code***: https://github.com/kbmrdw/Statistical_MachineLearning/blob/main/Nhom2_source_code.ipynb
