# KAIST_ME491B_HW1
Repository for KAIST ME491B HW1 code.

## Usage
Download catdog data in https://drive.google.com/file/d/1RGNDCsWGiI75Y1aLoMZ1C_AD-J9rnrce/view?usp=sharing and unzip in workspace.
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
https://www.dropbox.com/s/wvye28wmwpz6631/CNN_dogcat200928.pt?dl=0


## ME491(B) 2020 Fall, Code Review #1. CNN                                  

#### Due : 10/19 (Mon) (13:00), KLMS

- You can write the report in **English** or **Korean** / within 5 pages

___
### 1. Pytorch

(1) Explain the following pytorch libraries simply. (In two lines)

```
torch.nn.functional
torch.optim
torchvision
torch.autograd
```

(2) Explain the advantages of using GPU than CPU. (In one line)

___
### 2. CNN code review

Please download the codes and files in this repository.
https://github.com/Jong2/KAIST_ME491B_HW1

Write the code review report of two scripts (***transfer_learning_tutorial.py*** and ***CNN_test.py***).

**(1) Overall code review.**

- The code structure - comments on each meaningful code block. (You can capture the code in image, and give some comments on it)
- Explain the role of each code block.
- *e.g. This line defines the type of loss.*

Also, you are encouraged to train and test the network with fine-tuning, and check the effect of it.
The report should contain answers about these questions in maximum two lines each.

(2) How does the learning rate affect training?
(3) How does the preprocessing method (e.g. data augmentation, normalization) affect training?
(4) How does the epoch size affect training?
*e.g. If the learning rate gets bigger, something gets better while something gets worse. The reason is--* 

--> You don't need to do experiment to answer the questions (2)-(4), but if you analyze this by your own experiment and results, *extra points* might be given. You can still get a perfect score when you write the answer without conducting own experiments.

(5) If you changed the code better, please explain your code and results. You can also put the loss graph, comparison of training and test accuracy, etc. If you changed the code, please submit your code with the report. These tasks will be evaluated as *extra points*.

---

If you have any question, contact me by e-mail (Jonghwi Kim(김종휘), stkimjh@kaist.ac.kr)
Code reference : github/leeJaeDuck/cnn_learning_code
