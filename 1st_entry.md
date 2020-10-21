# First Entry of the Blog
 
## Relation between fib() and Haskell programming

I could see how recursion used in the fibonacci sequence played a roll in our Haskell <br/>
programming when we started coding for functional Programming. <br/>

Example 1 <br/>

'-- multiplication
mult :: NN -> NN -> NN
mult O n = O
mult (S O) n = n
mult (S n) m = add m (mult n m)'

## Downloading Haskell

 The instructions on GitHub helped make it less complicated. I saw though,in the <br/>
discussion that some people had more issues when using a Windows computer<br/>

Imperative languages are alot more easier to work than functional progamming languages <br/>
in my opinion. With Imperative languages, it is easier to give a computer <br/>
a task and then it executes them. Also during execution, it can change state. <br/>
With Functional Programming, like Haskell, it avoids mutable data and state <br/>
It's declarative rather than imperative.

Imperative

> x = 2 <br/>
> y = 3 <br/>
> x + y <br/>
> 5 <br/>
> x = 10 <br/>
> x + y <br/>
> 13 <br/>

Haskell

We defined the 'add' opertation for all NN using successor numbers.

' -- addition
add :: NN -> NN -> NN
add O n = n
add (S n) m = S (add n m)'


