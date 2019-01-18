# Reasons for concurrency and parallelism


To complete this exercise you will have to use git. Create one or several commits that adds answers to the following questions and push it to your groups repository to complete the task.

When answering the questions, remember to use all the resources at your disposal. Asking the internet isn't a form of "cheating", it's a way of learning.

 ### What is concurrency? What is parallelism? What's the difference?
 > Concurrency is fake parallelism, that is, a single processor running multiple tasks seemingly simultaneous. 
	Paralellism is when multiple processors run tasks independently and simultaneously.
 
 ### Why have machines become increasingly multicore in the past decade?
 > Several advantages relating to performance and implementation.
 
 ### What kinds of problems motivates the need for concurrent execution?
 (Or phrased differently: What problems do concurrency help in solving?)
 > Multiple modules of a program accessing shared resources.
 
 ### Does creating concurrent programs make the programmer's life easier? Harder? Maybe both?
 (Come back to this after you have worked on part 4 of this exercise)
 > Harder and easier!
 
 ### What are the differences between processes, threads, green threads, and coroutines?
 > They are very confusing :-1
 
 ### Which one of these do `pthread_create()` (C/POSIX), `threading.Thread()` (Python), `go` (Go) create?
 > This can be googled!
 
 ### How does pythons Global Interpreter Lock (GIL) influence the way a python Thread behaves?
 > Not sure
 
 ### With this in mind: What is the workaround for the GIL (Hint: it's another module)?
 > Don't know
 
 ### What does `func GOMAXPROCS(n int) int` change? 
 > Just here to test github!
