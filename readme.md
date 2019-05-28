* 优达学城 机器学习纳米学位 非监督学习  创建客户细分项目

## 项目要求

* 近日，一家批发经销商尝试着针对一些客户改变其发货方式，从原来的每周五次每次早上发货，改为了更为便宜的每周三次每次晚上发货。起初，
发货方式的改变并没有带来任何显著的负面结果，于是该批发商将这一更为便宜的变动推广到了所有客户。几乎同一时刻，
该批发商开始收到客户对发货服务变动的投诉，也有的客户开始取消提货。该批发商受到的损失比节省下来的钱还要多。
现在，该批发经销商雇佣你，希望你确定他们的客户特征和信息，以帮助它们在未来做出更加明智的商业决策。你的任务就是利用非监督学习技术，
看看客户之间存在哪些相似之处，以及如何以最佳的方式将客户细分为不同类别。


## 代码说明

### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. Make sure that you select the Python 2.7 installer and not the Python 3.x installer. 

### Code

Template code is provided in the `customer_segments.ipynb` notebook file. You will also be required to use the included `visuals.py` Python file and the `housing.csv` dataset file to complete your work. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project. Note that the code included in `visuals.py` is meant to be used out-of-the-box and not intended for students to manipulate. If you are interested in how the visualizations are created in the notebook, please feel free to explore this Python file.

### Run

In a terminal or command window, navigate to the top-level project directory `customer_segments/` (that contains this README) and run one of the following commands:

```bash
ipython notebook customer_segments.ipynb
```  
or
```bash
jupyter notebook customer_segments.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

## Data

The customer segments data is included as a selection of 440 data points collected on data found from clients of a wholesale distributor in Lisbon, Portugal. More information can be found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers).

Note (m.u.) is shorthand for *monetary units*.

**Features**
1) `Fresh`: annual spending (m.u.) on fresh products (Continuous); 
2) `Milk`: annual spending (m.u.) on milk products (Continuous); 
3) `Grocery`: annual spending (m.u.) on grocery products (Continuous); 
4) `Frozen`: annual spending (m.u.) on frozen products (Continuous);
5) `Detergents_Paper`: annual spending (m.u.) on detergents and paper products (Continuous);
6) `Delicatessen`: annual spending (m.u.) on and delicatessen products (Continuous); 
7) `Channel`: {Hotel/Restaurant/Cafe - 1, Retail - 2} (Nominal)
8) `Region`: {Lisnon - 1, Oporto - 2, or Other - 3} (Nominal) 