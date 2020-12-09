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


## Usage


## Results


## Contributing

### Conntributors
Team Name: GFZ

Team Member: <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Bei Zhao - beizhao3 (Captain) <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Ryan Fraser - rfraser3 <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Yiming Gu - yimingg7 <br />

## License

