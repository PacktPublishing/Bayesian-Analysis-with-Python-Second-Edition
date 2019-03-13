# Bayesian-Analysis-with-Python-Second-Edition
Bayesian Analysis with Python - Second Edition, published by Packt

---
**Please find the accompanying code and figures [here](https://github.com/aloctavodia/BAP)**

---

<a href="https://www.packtpub.com/big-data-and-business-intelligence/bayesian-analysis-python-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781789341652"><img src="https://d255esdrn735hr.cloudfront.net/sites/default/files/imagecache/ppv4_main_book_cover/B11197_0.png" alt="Book Name" height="256px" align="right"></a>

This is the code repository for [Bayesian-Analysis-with-Python-Second-Edition](https://www.packtpub.com/big-data-and-business-intelligence/bayesian-analysis-python-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781789341652), published by Packt.


## What is this book about?
The second edition of Bayesian Analysis with Python is an introduction to the main concepts of applied Bayesian inference and its practical implementation in Python using PyMC3, a state-of-the-art probabilistic programming library, and ArviZ, a new library for exploratory analysis of Bayesian models.

This book covers the following exciting features: 
* Build probabilistic models using the Python library PyMC3 
* Analyze probabilistic models with the help of ArviZ
* Acquire the skills required to sanity check models and modify them if necessary 
* Understand the advantages and caveats of hierarchical models
* Find out how different models can be used to answer different data analysis questions

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1788996348) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>


## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
with pm.Model() as our_first_model:
 θ = pm.Beta(' θ', alpha=1., beta=1.)
 y = pm.Bernoulli('y', p=θ, observed=data)
 trace = pm.sample(1000, random_seed=123)
```

**Following is what you need for this book:**
If you are a student, data scientist, researcher, or a developer looking to get started with Bayesian data analysis and probabilistic programming, this book is for you. The book is introductory so no previous statistical knowledge is required, although some experience in using Python and NumPy is expected.

With the following software and hardware list you can run all code files present in the book (Chapter 1-9).

### Software and Hardware List

| Chapter  | Software required                   | OS required                        |
| -------- | ------------------------------------| -----------------------------------|
| 1-8      | IPython 7.0.1                       | Windows, Mac OS X, and Linux (Any) |
|          | Jupyter 1.0 (or Jupyter-Lab 0.35)   | Windows, Mac OS X, and Linux (Any) |
|          | NumPy 1.14.2                        | Windows, Mac OS X, and Linux (Any) |
|          | SciPy 1.1.0                         | Windows, Mac OS X, and Linux (Any) |
|          | Pandas 0.23.4                       | Windows, Mac OS X, and Linux (Any) |
|          | Matplotlib 3.0.2                    | Windows, Mac OS X, and Linux (Any) |
|          | Seaborn 0.9.0                       | Windows, Mac OS X, and Linux (Any) |
|          | ArviZ 0.3.1                         | Windows, Mac OS X, and Linux (Any) |
|          | PyMC3 3.6                           | Windows, Mac OS X, and Linux (Any) |

We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://www.packtpub.com/sites/default/files/downloads/9781789341652_ColorImages.pdf).


### Related products <Other books you may enjoy>
* Building Machine Learning Systems with Python - Third Edition [[Packt]](https://www.packtpub.com/big-data-and-business-intelligence/building-machine-learning-systems-python-third-edition?utm_source=github&utm_medium=repository&utm_campaign=9781788623223) [[Amazon]](https://www.amazon.com/dp/1788623223)

* Machine Learning Algorithms - Second Edition [[Packt]](https://www.packtpub.com/big-data-and-business-intelligence/machine-learning-algorithms-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781789347999) [[Amazon]](https://www.amazon.com/dp/1789347998)

## Get to Know the Author
**Osvaldo Martin**
Osvaldo Martin is a researcher at The National Scientific and Technical Research Council (CONICET), in Argentina. He has worked on structural bioinformatics of protein, glycans, and RNA molecules. He has experience using Markov Chain Monte Carlo methods to simulate molecular systems and loves to use Python to solve data analysis problems.
He has taught courses about structural bioinformatics, data science, and Bayesian data analysis. He was also the head of the organizing committee of PyData San Luis (Argentina) 2017. He is one of the core developers of PyMC3 and ArviZ.



## Other books by the author
* [Bayesian Analysis with Python](https://www.packtpub.com/big-data-and-business-intelligence/bayesian-analysis-python?utm_source=github&utm_medium=repository&utm_campaign=9781785883804)


### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSdy7dATC6QmEL81FIUuymZ0Wy9vH1jHkvpY57OiMeKGqib_Ow/viewform) if you have any feedback or suggestions.
