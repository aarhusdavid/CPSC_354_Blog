# Second Entry of the Blog

## Discrete vs Programming Languages

When we first started discussion in class I quickly saw correlation<br/>
between discrete mathematics and programming languagess.For the readers <br/>
that don't know what Discrete mathematics is, according to Google, <br/>
"It is the study of mathematical structures that are countable or otherwise <br/>
distinct and separable. Examples of structures that are discrete are <br/>
combinations, graphs, and logical statements. Discrete structures can be <br/>
finite or infinite.

In discrete we  began by simplfying the simplest operations in math including counting <br/>

### Successor Math 
 
1. 3 = 0->->->
2. 3 = 1 + 0->->
3. 3 = 2 + 0->>
4. 3 = 3
		
This successor logic is what we used in our fraction.hs file to define NN

### List

We see the same sort of logic in lists. Also I thought the abbreviation for lists <br/> 
in Haskell was very similar to what we saw in Discrete Mathematics. 

Example

'append [] ys = ys
append (x:xs) ys = x:(append xs ys)'

'less_equal [] [] = True
less_equal (x:xs) (y:ys) = (x <= y) && less_equal xs ys'

3:(6:(2:(1:[])))



