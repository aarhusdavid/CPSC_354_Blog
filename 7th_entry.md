# 7th Blog Entry


## Programming Languages and Machine Learning <br/>

[Article](https://blog.acolyer.org/2020/01/15/programmatically-interpretable-reinforcement-learning/) <br/>

I thought it was interesting how the article started off by saying there were so many deployment benefits <br/>
even putting aside any ethical or safety concern. <br/>

We had a discussion about This in one of my classes last year "Ethics in Computing". One of the projects was to <br/>
present to the class an topic that dealt with ethics in computing in the real world. I decided to chose the topic <br/>
of self driving cars, specifically with Tesla. <br/>

I was main fascinated with the dilemma a car would have to face when put in a situation where it had to decide between <br/>
the life of the person in the car or a innocent kid just crossing the street. In this situation, the car would use it's <br/>
machine learning capabiliites to swerve and dodge a kid who was simply just crossing the street at the wrong time. However <br/>
this would be at the expense of the passenger who might have to pay with his or her own life due to the abrupt swerve. <br/>
Do these ethics lie on the hands of the engineers who coded the machine? Or is it the cars responsibiliry who has already <br/>
consumed and calculated an immense amount of data and scenarios which has primed itself to be prepared for almost anything. <br/> 

Adrian Colyer, the author of this article, argues that programmatically interpretable reinforcement learning has benefits that <br/>
outweight any sort of situation. 

To start off how would you even begin to make an interpretable model? Much like in our CPSC 354 course, the article suggests you <br/> 
you would start off by defining a grammar and associated semantics in which the model would express itself. It is important that <br/>
this language be interpretable for the machine, which will enable 'black box methods'. Here is a snippet of the article to further <br/> 
explain black box policy. 

> Hence black-box and other models become not the ultimate output of our learning process, but an intermediate step along the way. <br/>
> In PIRL, Verma et al. embody this pattern in the following way:
> 1. There’s a tiny functional language based on a small number of side-effect free combinators
> 2. For a given task, a program template (which the authors call a sketch), further constrains the set of programs that can be learned <br/>
> for the problem in hand. This also very handily constrains the search space of course, helping to make learning a suitable policy <br/>> 
> program tractable.
> 3. To help guide the search within the set of programs conforming to the sketch, a standard reinforcement learning algorithm is used <br/>
> to learn a (black box) policy.
> 4. The black box policy is used as an oracle (the Neural Policy Oracle), and a neurally directed program search (NDPS) tries to find <br/>
> the sketch-conforming program that behaves as closely to the oracle as possible.

