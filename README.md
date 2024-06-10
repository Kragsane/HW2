# DL_HW2

Hello, this is a github repo for NCKU Data Science's Deep Learning Class HW2.
We use mini-ImageNet dataset which is a smaller version of the ImageNet dataset with 50 classes, created to reduce the computational complexity while retaining the essential properties of the larger dataset. (The image folder can be request by email).

It will be divided into 2 tasks (parts).
Task 1: Designing a Convolution Module for Variable Input Channels
Task 2: Designing a Two-to-Four-Layer Network for Image Classification


The image inserted into our model will first being processed using 'preprocess.ipynb' into a 224 x 224 x 3 image size, and save into 3 different npz, which is 'train.npz', 'val.npz', and 'test.npz'.

Folder and file explained:
- The file #.ipynb# is a code file containing the code to do the task. It is divided into "Part1_xx" for completing task 1, and "Part2_xx" for completing task 2.
- The file "ResNET18" and "ResNET34" is the baseline model (naive model) use as comparison with our model. "ResNET18" compares with models from task 1, and "ResNET34" compares with model from task 2.
- The folder "Part1" and "Part2" contains the model and predicted results saved in .csv file so that we don't have to retrain the model every single time we want to use it (except to reproduce, which is actually don't need as we can insert the model and evaluate model's architecture).

To reproduce results to see model's architecture and predicted results without retraining:
1. Change "work_path" in cell 1 to match folder directory.
2. Run all cells except for cell starting with "num_epochs = 50" as this indicates training process.

For details on how to do these 2 tasks, please read the "report.docx" provided.

RE6125015