# Central limit project | EPITA 2022

## Observations
1) When I plot **both the mean and the sum** from the same sample, the results in the plot are the same since it is related to the same sample.
2) I tried using different values, one of the best distributions I have are the following:
   1) **Tosses:** 1.000.000 / **Samples:** 1.000 / **Size of samples:** 5.000
   2) **Tosses:** 1.000.000 / **Samples:** 10.000 / **Size of samples:** 50.000
   3) **Tosses:** 1.000.000 / **Samples:** 50.000 / **Size of samples:** 100.000 `This takes some more time than others`
3) I also added the bell shape to the figure when we receive inputs from the user.
4) I used only `numpy` and `matplotlib` as libraries since numpy also provides the *random function*.
5) I use **list comprehension** when it comes to select the indexes for the sample. It is easier and we avoid having a for loop for it. Besides that, we use `range` for that too to facilitate the process and extraction of samples.
6) I calculated the bell using the **mean** and the **standard deviation** of the means (from l2). In this way, we can simulate the curve it generates.
7) In the last part of the notebook, I iterated it to show the progression when the population, the size of sample and the number of samples increases. It is pretty interesting the evolution of the graphics.