## Hello everyone .. Today we will learn something beautiful and new in our course 401 :fire: :fire: .. Please have fun :blush: :sunglasses: :heart_eyes:

# Dunder method : 
Dunder or magic methods in Python are the methods having two prefix and suffix underscores in the method name. Dunder here means “Double Under (Underscores)”. These are commonly used for operator overloading. Few examples for magic methods are: __init__, __add__, __len__, __repr__ etc.

The __init__ method for initialization is invoked without any call, when an instance of a class is created, like constructors in certain other programming languages such as C++, Java, C#, PHP etc. These methods are the reason we can add two strings with ‘+’ operator without any explicit typecasting.

Here’s a simple implementation :
filter_none

edit

play_arrow

brightness_4
# declare our own string class 
class String: 
      
    # magic method to initiate object 
    def __init__(self, string): 
        self.string = string 
          
# Driver Code 
if __name__ == '__main__': 
      
    # object creation 
    string1 = String('Hello') 
  
    # print object location 
    print(string1) 

Output :

<__main__.String object at 0x7fe992215390>


![](https://miro.medium.com/max/1200/0*2qlxUkQRsQdiM7MU.jpg)


# What is probability ?? 
At the most basic level, probability seeks to answer the question, “What is the chance of an event happening?” An event is some outcome of interest. To calculate the chance of an event happening, we also need to consider all the other events that can occur. The quintessential representation of probability is the humble coin toss. In a coin toss the only events that can happen are:

    Flipping a heads
    Flipping a tails

From statistics to probability Our data will be generated by flipping a coin 10 times and counting how many times we get heads. We will call a set of 10 coin tosses a trial. Our data point will be the number of heads we observe. We may not get the “ideal” 5 heads, but we won’t worry too much since one trial is only one data point. If we perform many, many trials, we expect the average number of heads over all of our trials to approach the 50%. The code below simulates 10, 100, 1000, and 1000000 trials, and then calculates the average proportion of heads observed. Our process is summarized in the image below as well. 


![](https://i.imgur.com/3TuDF4G.jpg)


# what exactly is being distributed?

It depends on the context. In probability, the normal distribution is a particular distribution of the probability across all of the events. The x-axis takes on the values of events we want to know the probability of. The y-axis is the probability associated with each event, from 0 to 1.

the normal distribution is a particularly important kind of probability distribution. In statistics, it is the values of our data that are being distributed. Here, the x-axis is the values of our data, and the y-axis is the count of each of these values. Here’s the same picture of the normal distribution, but labelled according to a probability and statistical context: 


![](https://www.teampay.co/wp-content/uploads/2020/05/Traditional-Spending-Model-vs-Distributed-Spending-Model.png)


