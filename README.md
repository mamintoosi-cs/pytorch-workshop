PyTorch Workshop
==========
 [![repo size](https://img.shields.io/github/repo-size/mamintoosi-cs/pytorch-workshop.svg)](https://github.com/mamintoosi-cs/pytorch-workshop/archive/master.zip)
 [![GitHub forks](https://img.shields.io/github/forks/mamintoosi-cs/pytorch-workshop)](https://github.com/mamintoosi-cs/pytorch-workshop/network)
[![GitHub issues](https://img.shields.io/github/issues/mamintoosi-cs/pytorch-workshop)](https://github.com/mamintoosi-cs/pytorch-workshop/issues)
[![GitHub license](https://img.shields.io/github/license/mamintoosi-cs/pytorch-workshop)](https://github.com/mamintoosi-cs/pytorch-workshop/blob/main/LICENSE)

This is a tutorial to be presented during a [workshop](http://cnf.hsu.ac.ir/esla/fa/page.php?rid=91) at The 11th Seminar on Linear Algebra and its Applications 2022.

# Slides
[Slides](https://mamintoosi.github.io/slides/topics/DL-HSU/DeepLearning-Workshop-ESLA2022.html)

### Using Google Colab
The Google Colab notebooks are available under:
- [1-Basics.ipynb](https://colab.research.google.com/github/mamintoosi-cs/pytorch-workshop/blob/master/1-Basics.ipynb)
- [2-Autograd.ipynb](https://colab.research.google.com/github/mamintoosi-cs/pytorch-workshop/blob/master/2-Autograd.ipynb)
- [3-Regression_Gradient_Descent.ipynb](https://colab.research.google.com/github/mamintoosi-cs/pytorch-workshop/blob/master/3-Regression_Gradient_Descent.ipynb)
- [4-MLP-Digit-Recog.ipynb](https://colab.research.google.com/github/mamintoosi-cs/pytorch-workshop/blob/master/4-MLP-Digit-Recog.ipynb)
- [5-CNN-CIFAR.ipynb](https://colab.research.google.com/github/mamintoosi-cs/pytorch-workshop/blob/master/5-CNN-CIFAR.ipynb)
- [6-Transfer-Learning.ipynb](https://colab.research.google.com/github/mamintoosi-cs/pytorch-workshop/blob/master/6-Transfer-Learning.ipynb)


In order to use Google Colab, you have to login using your Google account:
![Google Colab Login](figures/colab-connect.png)

### Changing the runtime type
You can add GPU support on Google Colab by changing the runtime type as depicted below:

![Google Colab Runtime](figures/colab-runtime.png)
<br />

## During the Workshop
During the workshop, we recommend to use **Google Colab**. 
If you want to run the notebooks again later, you can use the following setup using [Anaconda](https://www.anaconda.com/). Unfortunately, we won't have time to help you with your conda installation. 
<br />

## Using conda
If you want to run the notebooks locally, you can use `conda`. The following instructions
should work on Linux/Mac OS, Windows might require slight adaptations.

### Step 1: Install conda
If you have not installed it yet, you can download it from [Anaconda (Python version > 3.5)](https://www.anaconda.com/download).

### Step 2: Download repository 
Now clone the repository:
```bash
git clone https://github.com/mamintoosi/pytorch-workshop.git
cd pytorch-workshop
```

### Step 3: Install requirements' packages

Now start the Jupyter notebook by running
```bash
pip install -r requirements.txt
```

Now start the Jupyter notebook by running
```bash
jupyter notebook
```

## Additionnal resources:
Check out these others tutorials and courses:

<div dir="rtl">
							امین‌طوسی، محمود (۱۳۹۹)،
							<a href="https://math-sci.ui.ac.ir/article_25351.html">
								کاربرد بسط تیلور در کاهش حجم شبکه‌های عصبی پیچشی برای طبقه‌بندی نقاشی‌های سبک
								امپرسیونیسم و مینیاتور.
							</a>
							نشریه ریاضی و جامعه،‌ ۵ (۱)،‌ ۱-۱۶.
</div>							 
- Official tutorials : https://pytorch.org/tutorials/
- PyTorch for DL (.py files): https://github.com/yunjey/pytorch-tutorial
- PyTorch for DL (notebooks): https://github.com/yandexdataschool/Practical_DL
- PyTorch for Numpy users : https://github.com/wkentaro/pytorch-for-numpy-users
