# Overview of Numpy Random package. Sam Tracey (Student ID: G00398245)

***

This repository is my submission for the Programming for Data Analysis module (2021) as part of the Higher Diploma in computing in Data Analytics at GMIT.

***

## Assignment Overview

**Problem Statement**<br>

The following assignment concerns the numpy.random package in Python. You are
required to create a Jupyter notebook explaining the use of the package, including
detailed explanations of at least five of the distributions provided for in the package.
There are four distinct tasks to be carried out in your Jupyter notebook.

1. **Explain the overall purpose of the package.**
2. **Explain the use of the “Simple random data” and “Permutations” functions.**
3. **Explain the use and purpose of at least five “Distributions” functions.**
4. **Explain the use of seeds in generating pseudorandom numbers.**

***

## Downloading The Code

- If you have not done so already please visit: https://www.anaconda.com/products/individual to download the latest version of Anaconda.

- Go to the following URL: https://github.com/Sam-Tracey/numpy-random/ and clone the repository. The original repository is set to Public.

- Once downloaded, navigate to the folder in which you stored the repository using your Command Line Interface. In this project I used cmder which can be downloaded here: https://cmder.net/

- At your CLI prompt type <code>jupyter lab</code> to launch Jupyter lab.

- Click on the numpy-random.ipynb file in the left hand pane.

- Once loaded, select Run > Run All Cells to execute the code.

- The notebook with all its code and output can be viewed online directly in the [Github repository](https://nbviewer.org/github/Sam-Tracey/numpy-random/blob/main/numpy-random.ipynb) without downloading anything from the repository. If, for some reason, it fails to render, a fully rendered version has been saved at the following location:https://nbviewer.org/github/Sam-Tracey/numpy-random/blob/main/numpy-random.ipynb

***

## About This Project

The latest version of NumPy at the time of writing was V1.21 and this is what was used exclusively in this project. The full documentation for NumPy V1.21 can be found here: [NumPy Documentation](https://numpy.org/doc/stable/)

In the first section of the notebook I give a brief overview of NumPy and the <code>numpy.random</code> package.
The next section gives an overview (in my own words) of the following functions with graphical representations using matplotlib.pyplot and seaborn:

- <code>numpy.random.rand</code>
- <code>numpy.random.randn</code>
- <code>numpy.random.randint</code>
- <code>numpy.random.choice</code>
- <code>numpy.random.random_sample</code>
- <code>numpy.random.bytes</code>


The next section discusses two permutation functions:

- <code>numpy.random.shuffle</code>
- <code>numpy.random.permutation</code>

In the distribution section I give overviews of five different numpy distributions with practical examples where possible. Again, there are charts created using matplotlib.pyplot and seaborn to visualise the key aspects and differences in the following distributions:

- <code>numpy.random.normal</code>
- <code>numpy.random.exponential</code>
- <code>numpy.random.uniform</code>
- <code>numpy.random.weibulll</code>
- <code>numpy.random.binomial</code>


The final section details the use of seeds in generating pseudo-random numbers.


***
## References

Throughout this assignment I carried out extensive research involving work from various institutions and individuals who are highly regarded in their field. Below is a list of references:

[1] Harris, C.R., Millman, K.J., van der Walt, S.J. et al. Array programming with NumPy. Nature 585, 357–362 (2020). Available at:https://doi.org/10.1038/s41586-020-2649-2<br>
    accessed 24th October 2021<br>
[2] Bonner, A. The Ultimate Beginner’s Guide to NumPy. Towards Data Science (2019). Available at: https://towardsdatascience.com/the-ultimate-beginners-guide-to-numpy-f5a2f99aef54 <br> accessed 24th October 2021<br>
[3] numpy.org, What is NumPy? 2021. Available at: https://numpy.org/doc/stable/user/whatisnumpy.html accessed 24th October 2021<br>
[4] Gough, C. Performance of Numpy Array vs Python List (2019). Available at: https://medium.com/@gough.cory/performance-of-numpy-array-vs-python-list-194c8e283b65 accessed 24th October 2021.<br>
[5] McKinney, M. Python for Data Analysis. 120-124 (2018).<br>
[6] Micorsoft (2021). CryptGenRandom function (wincrypt.h). Available at:https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgenrandom?redirectedfrom=MSDN accessed 24th October 2021.<br>
[7] Hosch, L. W, Britannica. Uniform Distribution. Available at: https://www.britannica.com/topic/uniform-distribution-statistics accessed 31st October 2021.<br>
[8] numpy.org, numpy.random.randint. Available at: https://numpy.org/doc/stable/reference/random/generated/numpy.random.randint.html accessed 31st October 2021 <br>
[9] Weisstein, Eric W. "Interval." From MathWorld--A Wolfram Web Resource. Available at: https://mathworld.wolfram.com/Interval.html accessed November 11th 2021 <br>
[10] Van Rossum, G. PEP 3137 -- Immutable Bytes and Mutable Buffer (2007). Available at: https://www.python.org/dev/peps/pep-3137/ accessed November 11th <br>
[11] W3 Schools, Random Permutations. Available at: https://www.w3schools.com/python/numpy/numpy_random_permutation.asp accessed November 11th 2021<br>
[12] Pathak, M. Probability Distributions in Python Tutorial (2019). Available at: https://www.datacamp.com/community/tutorials/probability-distributions-python accessed 9th November 2021<br>
[13] O'Donnell, A., Buffini, M., Kehoe, L., Nugent, A., Kearney, J., Walton, J., Flynn, A., & McNulty, B. (2020). The prevalence of overweight and obesity in Irish children between 1990 and 2019. Public Health Nutrition, 23(14), 2512-2520. Available at:  https://doi.org/10.1017/S1368980020000920 accessed 9th November 2021<br>
[14] U.S Department of Commerce, Measures of Skewness and Kurtosis. Engineering Statistics Handbook (2013) Available at:https://www.itl.nist.gov/div898/handbook/eda/section3/eda35b.htm, accessed November 13th 2021<br>
[15] National Library of Medicine, Standard Deviation. Available at: https://www.nlm.nih.gov/nichsr/stats_tutorial/section2/mod8_sd.html accessed 13th November 2021.<br>
[16] Reliawiki.org, The Exponential Distribution (2017). Available at: https://reliawiki.org/index.php/The_Exponential_Distribution accessed 13th November 2021<br>
[17] Frost, J. Weibull Distribution (2021). Available at: https://statisticsbyjim.com/probability/weibull-distribution/ accessed 1th November 2021.<br>
[18] Reliability Hot Wire, Weibull.com. Available at:https://www.weibull.com/hotwire/issue14/relbasics14.htm accessed November 15th 2021.<br>
[19] Weisstein, Eric W. "Pseudorandom Number." From MathWorld--A Wolfram Web Resource. Available at: https://mathworld.wolfram.com/PseudorandomNumber.html accessed 17th November 2021<br>
[20] Meiss, J. Dynamical Systems (2017). Available at: http://dx.doi.org/10.4249/scholarpedia.1629, accessed 17th November 2021<br>
[21] Wikipedia, List of Random Number Generators (2021). Available at: https://en.wikipedia.org/wiki/List_of_random_number_generators accessed 17th November 2021.<br>
[22] O'Neil, M.E. Specific Problems with other RNGs (2018). Available at: https://www.pcg-random.org/other-rngs.html accessed 17th November 2021.<br>



 













