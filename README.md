<p align="center">
  <a href="">
    <img src='https://ibb.co/mrnrxkT' alt="HuzaLabs logo" width = 100px>
   </a>
</p>
<h3 align="center"><a href='https://www.huzalabs.com/'> HuzaLabs </a></h3>
<h4 align="center">NLP Hackathon: AI Chatbot</h4>


**Table of content**

- [Project Overview](#Project_Overview)
- [Installation](#installation)
- [Requirements](#Requirements)
- [Usage](#Usage)
- [Contacts](#Contacts)

## Project_Overview

The purpose of this project is to create AI chatbot that shall help users knowing basic information about the company by interacting with them.


## installation 
```
git clone https://github.com/skevin-dev/NLP-Second-hackathon-AI-Chatbot
cd NLP-Second-hackathon-AI-chatbot

```
For Installation of PyTorch see [official website](https://pytorch.org/).

You also need `nltk`:
 ```console
pip install nltk
 ```

If you get an error during the first run, you also need to install `nltk.tokenize.punkt`:
Run this once in your terminal:
 ```console
$ python
>>> import nltk
>>> nltk.download('punkt')
```

## Requirements

* pandas 
* BeautifulSoup
* requests
* numpy 
* json

## Usage

## Usage
Run
```console
python train.py
```
This will dump `data.pth` file. And then run
```console
python chat.py
```
## Contacts


👤 **Shyaka Kevin**
- LinkedIn: [Shyaka Kevin](https://www.linkedin.com/in/shyaka-kevin/)