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

When we first downloaded Haskell it was unlike any Imperative language that I have ever. <br/>
Downloaded. The instructions on GitHub helped make it less complicated. I saw though, in the <br/>
discussion that some people had more issues when using a Windows computer<br/>

Imperative languages are alot more easier to work with because they are alot <br/>
more straight forward. You can initialize variables and objects very easily <br/>
whereas in Haskell we were defining for all NN or PN.

Imperative

> x = 2
> y = 3
> x + y
> 5

Haskell

We defined the 'add' opertation for all NN using successor numbers.

' -- addition
add :: NN -> NN -> NN
add O n = n
add (S n) m = S (add n m)'


