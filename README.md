# Grad Project Files - *Changelog* <!-- omit in toc -->

## Table of Contents <!-- omit in toc -->

- [Week 5](#week-5)
- [Week 4](#week-4)
- [Week 3](#week-3)
- [Week 2](#week-2)

## Week 5

Feb 6:

- (Adam) Added a script for NLP model
  - Reorganized `Scripts` folder into 2 parts; Data & Model
    - `Scripts/Data` holds all the scripts related to data extraction
    - `Scripts/Model` holds the python code for the NLP model
  - Updated `Encoder_Decoder_V4` file to  save model in H4 format
  - Added `Scripts/Model` folder
    - `NLP_Model.py`: Refactored the python notebook code
    - `functions.py`: Unimportant functions moved to this
    - `myVars.txt`: Dependant variables that take the longest time to load are now saved in here (over a pkl file for readability)
    - Incomplete task: Change the decoder function code to take user inputs

## Week 4

Feb 5:

- (Adam) Added Encoder_Decoder V4
  - Removed .pkl files as they are not required (check commit description for more details)
  - Added a file with the dataset rows doubled for testing

## Week 3

Jan 25:

- (Ayesha) Dataset Addition from this site <https://www.lifeprint.com/asl101/index/sign-language-phrases.htm>
- (Adam) Made changes to the Encoder_Decoder Notebook for the PoC Presentation

Jan 23:

- (Ayesha) Dataset changes
  - Removing all maths sentences
  - Some sentences had 3 lines (removing those sentences)
- (Ayesha) Fix for [removingSpacesFromDataset.py](removingSpacesFromDataset.py): Previous code wasn't iterating properly and was pasting the same sentences twice
- (Adam) Reorganized repository

Jan 22: (Adam) Added [Encoder_Decoder_V2.ipynb](Encoder_Decoder_V2.ipynb): 2nd Version of EncoderDecoder

Jan 20: (Ayesha) New dataset added, has around 2K rows of data & script written by her

## Week 2

Jan 19: Updated python notebook with completed encoder-decoder code. Still needs a lot of improvements

Jan 17: Repo set up
