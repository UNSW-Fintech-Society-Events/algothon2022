# Algothon101 + Resources

## **IMPORTANT** ##

The following materials serve as supplementary resources to our Algothon workshops. Please refer to the workshop recordings to understand key skills for the competition.

Please note that the workshop will not provide all required knowledge for the competition. Additional research will be required, and below provides a great start!!

## Workshop Resources ##

### Workshop 1 (Python) Links
> Click [here](https://zoom.us/rec/share/sF8EVA8-_VaUEnGM-3ZoIgSbD5bYyGoW1TXnYD1U71-A0PHdR_8DU116lU2Ab5Qi.OhWS8Dh6lV2ibvC9) for the recording.

> Click [here](https://unsw-my.sharepoint.com/:p:/g/personal/z5363065_ad_unsw_edu_au/EU0JccsEvXpAqg_s6zTMS2MBR3nhdrKBAT9pcOBlouPE_g?rtime=DCx2B_5U2kg) for the workshop slides.

> Click [here](https://replit.com/@UNSW-Fintech-So/AlgothonWorkshop1-Overview#main.py) for the workshop codebase.

### Workshop 2 - Algorithmic Trading Links

> Click [here](https://drive.google.com/file/d/1qJPwl48jnsaiHP7QxfK7TlED60zx0UO2/view?usp=sharing) for the workshop slides.

### Kick-off / Q&A Event Links

> Click [here](https://drive.google.com/file/d/1G0wvL4JEmI67sesG6Sew-xuha0aIqR70/view?fbclid=IwAR2qx_o0H80EoLasI_0h7pxUlPSb4gmBrNBczCfZgeWARtuQhxkI1wlNmPI) for the slides.

## Guidance

The following is provided only as guidance, to assist with direction in completing this challenge. You can choose to use any, none or all of it, given that your submission fall within the specified criteria. We would like to see different models developed in the competition, and any projects that address the investment themes will have a fair chance at winning!


There are almost infinite free resources online regarding both the financials and technicals required in algorithmic trading, but we've compiled a bunch we think are useful!

**Basics**

- [Beginner's Guide to Quantitative Trading](https://www.quantstart.com/articles/Beginners-Guide-to-Quantitative-Trading/)
- [How to Identify Algorithmic Trading Strategies](https://www.quantstart.com/articles/How-to-Identify-Algorithmic-Trading-Strategies/)
- Quantopian: [https://gist.github.com/ih2502mk/50d8f7feb614c8676383431b056f4291](https://gist.github.com/ih2502mk/50d8f7feb614c8676383431b056f4291)
    - *Quantopian has a bunch of lectures catering to various skill levels, from novices with no programming ability (intro to Python, NumPy, Pandas), to those who want to learn advanced linear regression, portfolio optimisation, beta hedging etc.*
- Learndatasci:
    
    [https://www.learndatasci.com/tutorials/](https://www.learndatasci.com/tutorials/)
    
    - *This site has a good range of resources related to quantitative analysis! There are some articles around dealing with NumPy and Pandas, as well as a good introduction to algorithmic trading. It even includes a detailed look at a moving-average strategy, with sample code!*

**Trading Strategies and Analytics**

- YouTube Series:
    - [Big Data Analytics & Algorithmic Stock Trading (Backtesting)](https://www.youtube.com/watch?v=u6Xd3kRHhJI&list=PLQVvvaa0QuDcR-u9O8LyLR7URiKuW-XZq)
    - [Machine Learning and Pattern Recognition for Algorithmic Stock Trading](https://www.youtube.com/watch?v=v_L9jR8P-54&list=PLQVvvaa0QuDe6ZBtkCNWNUbdaBo2vA4RO)
    - *These playlists are pretty extensive and cover a range of topics including basic instructions on how to access and manage stock data, calculating moving averages in Python etc.*
- Backtesting Algorithmic Trading Strategies: [Part 1](https://www.quantstart.com/articles/Successful-Backtesting-of-Algorithmic-Trading-Strategies-Part-I/) | [Part 2](https://www.quantstart.com/articles/Successful-Backtesting-of-Algorithmic-Trading-Strategies-Part-II/)
- [Backtesting a Mean Reversion Trading Strategy](https://medium.com/@dinodecastro/backtesting-a-trading-strategy-part-3-68191c970be7)
- [Stock Price Prediction with Python and Basic ML](https://www.youtube.com/watch?v=QIUxPv5PJOY)
- [Basic Tensorflow (Regression Problems)](https://www.youtube.com/watch?v=-vHQub0NXI4)

## Technical Advice

### Starting Out

For the Algothon, participants must have Python installed (v3.6+). We highly recommend using standard popular analytics/plotting libraries such as NumPy, Pandas and Matplotlib.

This can be done using the Anaconda package manager, which supports Windows, Linux and Mac. Other libraries such as TensorFlow and SciPy are also supported by Anaconda.

Install Anaconda [here](https://www.anaconda.com/distribution/).

### Data Sources

All data will be provided by FinTechSoc. The trading universe consists of simulated daily price data of 100 instruments. 

Preliminary round data will be provided at case release (7:00PM AEST 1 July). Note that the dataset used for judging will *not* be the same as the data provided to you.

Finalists will be provided the data used to assess preliminary rounds, and will have the opportunity to amend their algorithm. The dataset used to evaluate teams during final presentations will again be unseen data.  

### Heavy Computations

If you intend to perform large-scale computations, we would recommend setting up cloud computing resources to scale the training of your models. Getting an AWS Educate account will give you access to AWS credits without entering credit card details. 

Note that this should not be necessary given the volume of data provided by FinTechSoc. 

Join AWS Educate [here](https://aws.amazon.com/education/awseducate/).

Access documentation of various AWS products and tools [here](https://docs.aws.amazon.com/index.html?nc2=h_ql_doc_do_v).

Find examples for using Amazon SageMaker with the Python SDK [here](https://github.com/awslabs/amazon-sagemaker-examples/tree/master/sagemaker-python-sdk). SageMaker can be used to perform various machine learning tasks.