# KAIST_ME491C_HW2
Repository for KAIST ME491C HW2 code.

## Usage
Download catdog data in https://www.dropbox.com/s/dgfx1kx27pfdw2n/catdog_data.zip?dl=0 and unzip in workspace.

Original catdog_image source is https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/.

- To train a model(network):

```
$ python3 transfer_learning_tutorial.py
```

- To test the saved model(network):

```
$ python3 CNN_test.py
```
- You can also copy and paste these codes to Google Colab and run the codes.
- To use pretrained weights to test the network, download the file from the following link.
https://www.dropbox.com/s/6x5jitduoqc9wx8/CNN_dogcat200928.pt?dl=0

___

## ME491(C) 2021 Fall, Code Review #2. CNN                                  

#### Due : 10/27 (Wed) (13:00), KLMS

- You can write the report in **English** or **Korean** / within **7 pages** / **pdf**

### 1. CNN code review

Please download the codes and files from following link.
https://github.com/Jong2/KAIST_ME491B_HW1

Write the code review report of two scripts (***transfer_learning_tutorial.py*** and ***CNN_test.py***).

**(1) Overall code review (within 4 pages)**

- The code structure - comments on each meaningful code block (about 2 or 3 lines per block). You can capture the code in image, and give some comments on it.
- <u>Explain the role of each code block</u>. *e.g. This line defines the type of loss - SGD.*
- Run two scripts and <u>attach the test result images</u>.

**(2) Design your own CNN model for the catdog dataset (within 2 pages)**

- Design the model and write a code.
- Replace fine-tuned Res18 model by <u>your own CNN model</u>.
- Train and test the catdog dataset by your model.
- <u>In the report, explain the model and corresponding changed lines in train/test code, and show how the loss and accurcay converged. Also, attach the test result images.</u>

**(3) Extra points** **(within 1 page)** (If you complete "(1) overall code review"  perfectly, you can get maximum points though. Also, although you exceed the maximum score by getting extra points, you still get the maximum score.)

- You can train and test the network with analyzing the effect of the learning rate, epoch size, optimizer, etc.
- If you changed the code better, please explain your code and results. You can also put the loss graph, comparison of training and test accuracy, etc. If you changed the code, please submit your code with the report.

---

If you have any question, contact me by e-mail (Jonghwi Kim(김종휘), stkimjh@kaist.ac.kr)
