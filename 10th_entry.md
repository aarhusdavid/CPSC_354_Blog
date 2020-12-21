# 10th Blog Entry

## Why Scala?

I have heard of Scala in the past but never really looked into it. I came across this article and decided I would give it a read <br/>

First of all I thought it was interesting how the Scala language inferred data types. Apparently it does this by taking in <br/>
sub expressions, or those of atomic values like 42(Integer) ,true(Bool, etc. Then aggregates this information to decide what <br/>
type an expression is.

Another feature was how it has no static variables or methods. It's use of a singleton object allows the user to develop under <br/>
a single object in the source file. All variables are immutable by default unless specified otherwise.

Lazy Evalutation was an interesting one to me. Basically Scala delays evalutating expressions until it absolutely has to. They <br/>
call this 'call-by-need'. This can avoid repeated evaluatios. More benefits from Lazy Evaluation are listed below <br/>

> 1.  We can define control flow as abstractions instead of primitives.<br/>
2. We can define potentially infinite data structures.<br/>
3. Lazy evaluation improves performance.,br/>

The language is also similar to Java in a sense that it can run on a JVM (Jave Virtual machine) because the compiler turns the <br/>
source code into byte code. Also it supports object-oriented programming.


