# Tasks synchronization and parallelization #


The aim of this lab is to correctly organize computation using multiply processes/threads. 


### Variant 10 ###

Use Java, processes and java.nio.channels.AsynchronousSocketChannel and Future<T>. 
Binary operation - conjunction. 
Also generalized to n functions.

### Type of cancellation ###
By special key (Ctrl + C)


### Test cases: ###
|x  |F result  |F time  |G result   |G time   |Result  |
|---|---|---|---|---|---|
|0   |1   |1018ms   |1   |3021ms   |1|
|2   |0   |3020ms   |   |   |0|
|3   |   |   |0  |3012ms   |0|
|4   |1   |1020ms   |  |inf   |hangs|
|5   |   |inf   |1  |1016ms   |hangs|




### Please, make sure to run Main.java in terminal from jar-file that lies in out/artifacts/lab1_main_jar/lab1.main.jar ###