# targilon5-repo
git@github.com:TomGroman/targilon5-repo.git

on excersize 3 the the reason for the result is unpredictible because each time we run the project the threads will behave differently.

on excersize 4, the result is predictible and it is 20,000. now the threads working in sync and not interrupting each other's actions.

on excersize 5, the difference will be the specification, which means that that way the programmer can lock only a specific action and not the whole class which might be very heavy.

on excersize 6, the function will handle 2 threads that will run 10000000 itterations of raising the bar, unsynchronised. the method will print the bar and the time (by milisecconds) it took.

on excersize 7, it will do the same as excersize 6, but with syncing, the program will print always the same number (10000000), but it will take much much longer. on excersize 6 it took around 40 milisecconds, but in 7 it took over than 800 millisecconds (sometimes even more than a 1000).
