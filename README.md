# CS410 CourseProject(Text Classification Competition): Twitter Sarcasm Detection 

## Table of Contents

- [Background](#background)
- [Install](#install)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Background

This is a course project for CS410 Text Information Systems and is a part of a text classification competition, which involves twitter sarcasm detection.
In this competition, it is required that you classify a twitter response in a conversation into either 'sarcasm' or 'not sarcasm'.

### Data

The dataset is comprised of two jsonl files, including a train.jsonl for data training and a text.jsonl for text classification.

Each line of the training data set includes the following fileds:
- ***response*** :  the Tweet to be classified
- ***context*** : the conversation context of the ***response***
- ***label*** : `SARCASM` or `NOT_SARCASM` 
- ***id***:  String identifier for sample.

The text classification file (test datset) differs from the training dataset only in that the file lacks the label.

The size of training dataset is 5000 and the size of the test dataset is 1800.

### Output
The output of the project is a anwser.txt document, which includes both id of test sample and a label of either `SARCASM` or `NOT_SARCASM` predicted by the model.

## Install

You can run the whole project on [Google Colab](https://colab.research.google.com/). You don't have to install anything locally.

## Usage

Each of the ipynb file in the [Code](https://github.com/bzhao10/CourseProject/tree/main/Code) folder represents one solution in the competition.

- ***Step 1*** You can then download two jsonl files, one training data and one test data, in the dataset.
- ***Step 2*** You can download one of these ipynb files and open it on [Google Colab](https://colab.research.google.com/).
- ***Step 3*** Then, you need to upload the two jsonl files to [Google Colab](https://colab.research.google.com/) under the dataset folder in the project that you have opened in ***Step 2***.
- ***Step 4*** Run the code line by line using [Google Colab](https://colab.research.google.com/).

By following all the steps mentioned above, you will get an answer.txt file.

## Results


## Contributing

### Conntributors
Team Name: GFZ

Team Member: <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Bei Zhao - beizhao3 (Captain) <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Ryan Fraser - rfraser3 <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Yiming Gu - yimingg7 <br />

## License

