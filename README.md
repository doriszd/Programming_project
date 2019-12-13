# Data simulation

## Programming for Data Analysis

![alt text](Hormones.png)

### Author: Doris Zdravkovic

In this project I will:

1. Choose a real-world phenomenon that can be measured and for which I could collect at least one-hundred data points across at least four diﬀerent variables. 

2. Investigate the types of variables involved, their likely distributions, and their relationships with each other. 

3. Synthesise/simulate a data set as closely matching their properties as possible. 

4. Detail my research and implement the simulation in a Jupyter notebook 
 

### Downloading and updating the repository

1. Go to GitHub.
2. Navigate to the main page of the repository: https://github.com/doriszd/Programming_project/blob/master/project.ipynb
3. Under the repository name, click Clone or download
4. Save the repository to a local folder location on your computer.
5. Navigate to your target directory in the command line
6. To add new content on gitHub type add .
7. Type git commit -m "Write a message here"
8. To send it to gitHub type git push

### About Numpy

NumPy (Numerical Python) is a linear algebra library in Python. It is a very important library on which almost every data science or machine learning Python packages such as SciPy (Scientific Python), Matplotlib (plotting library), Scikit-learn, etc depends on to a reasonable extent. NumPy is very useful for performing mathematical and logical operations on Arrays. It provides an abundance of useful features for operations on n-arrays and matrices in Python. Find more information about numpy here: https://docs.scipy.org/doc/numpy-1.15.0/user/index.html

### Aim and Method

The aim of this work is to simulate data that would correspond real world phenomenon. I will look into the difference in weight when a person is going through some hormonal imbalance problems. I will focus on data that shows the influence of BMI and age of a person on weight gain.

I will assess relationship of weight and hormonal imbalances using numpy.random package to simulate data. So, this is not a research based on real-life data, it is based on simulation. Nevertheless, data will be programmed in order to show as close relationship with real-life data as possible. Numpy.random pseudorandom numbers are a sample of numbers that look close to true random numbers but are generated using some deterministic process. As computers can not produce random numbers itself, they need packages and algorithms that would deal with it. Numpy.random package is one of the libraries in Python that generates pseudorandom data.

### Variables

1. Age

Age is important variable in this research because as we move through the stages of life, our hormone levels fluctuate; aging means that we produce more of some hormones and less of others.

2. Weight

Weight gain occurs when you regularly eat more calories than you use through normal bodily functions and physical activity. But the lifestyle habits causing your weight gain aren't always obvious. Losing weight means eating fewer calories and burning more energy through physical activity.

3. Height

I have chosen to implement this variable since it is necessary to calculate Body Mass Index (BMI) which tells us a lot about the level of fat in human body. 

4. Body mass index (BMI)

Body mass index (BMI) is a value derived from the mass (weight) and height of a person.

5. Hormonal imbalance

Hormones are body's chemical messengers. Produced in the endocrine glands, these powerful chemicals travel around your bloodstream telling tissues and organs what to do. They help control many of your body's major processes, including metabolism and reproduction. 


### Data frame

My simulated data frame has 5 variables that I find relevant to see if there is any relationship between hormonal imbalance and weight changes in women. To see the relationship between these variables I will include some demographics like age. As I want to determine relationship between hormonal imbalance and weight I needed to include height variable to calculate Body Mass Index which will give us significant information about the shape of human body. 

### Conclusion

Since the aim of this work was to simulate data to show real world phenomenon I have chosen to present data related to weight gain and hormonal imbalance. Previous findings have shown that hormonal imbalance affects weight changes, especially weight gain. Data I got in numpy.random package simulation shows the same result. BMI is higher with those who have hormonal imbalance. I don't see difference in Age and BMI variables which makes sense as in real life there is no real connection between those 2 variables. It doesn't mean that BMI would get higher as women get older. Although there is a connection with the data in the real world, this work has its flaws that could be improved. Data would be more precise if I only focused on one type of hormonal imbalance, not all of them. It would be possible to find more accurate information about weight increase if I investigated only one hormonal issue as some hormonal changes can positively or negatively affect weight gain, hence, if necessary in future research with real life data I would investigate only one hormone (for example thyroid) and its effect on weight gain.