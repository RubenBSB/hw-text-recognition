# deepOCR

This is a school project in deep learning I am currently working on.

It consists in building a handwritten text recognition system using a CNC-LSTM-CTC architecture.

I have planned to use a language model later to analyse recognized words and improve the accuracy.

This [article](https://arxiv.org/pdf/1411.4389.pdf) was really helpful to understand the concept of Convolutional Recurrent Neural Network (CRNN).

## Data

I am using the [IAM Dataset](http://www.fki.inf.unibe.ch/databases/iam-handwriting-database) which includes about 115,000 labelled images of English words from more than 1500 handwritten letters.

## Use

You have to register to download the dataset. Once it is done, unzip it and place the 'words' directory and 'words.txt' file in the project repository as following :

```
deepOCR repository
├── data
│   ├── words
│   │   ├── a01
│   │   ├── a02
│   │   ├── ...
│   ├── words.txt
├── src
├── ...
```
