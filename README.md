# parallel_Computer_PartialSum
Task II: find out partial sums (100points)

(1)	Create a new directory with the name of lab12 and then get into this directory. 

(2)	Write a program named PartialSum.c such that each process will compute and print out a partial sum of N numbers. Set N=1000 in your program.

(3)	Compile your program

(4)	Define 10 tasks in job script file (job3), then process 0 will print out the partial sum of 1+2+…+100 (that is, ), process 1 will print out the partial sum of 101+102+…+200(that is,  ), …, process 9 will print out the partial sum of 901+902+…+1000(that is,  ),.
(Note: In this program, you can declare a constant N=1000 or use preprocessing statement #define N 1000.)

(5)	When your program is finished, submit your script file (job3) check in the current directory whether you have the related output file produced. Then open this file and check the content. You should have the following content:

Java module loaded - the system's JAVA is replaced by JDK 1.8.0_211

Partial sum from process 0 of total 10 is : 5050.<br>
Partial sum from process 6 of total 10 is : 65050.<br>
Partial sum from process 3 of total 10 is : 35050.<br>
Partial sum from process 7 of total 10 is : 75050.<br>
Partial sum from process 2 of total 10 is : 25050.<br>
Partial sum from process 9 of total 10 is : 95050.<br>
Partial sum from process 5 of total 10 is : 55050.<br>
Partial sum from process 4 of total 10 is : 45050.<br>
Partial sum from process 8 of total 10 is : 85050.<br>
Partial sum from process 1 of total 10 is : 15050.<br>

(6)	Revise your script file to apply for 16 tasks, and then run your program again. Name this job job4.
