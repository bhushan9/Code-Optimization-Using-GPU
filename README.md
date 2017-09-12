<h2>Description</h2> 
This project is about optimizing given CUDA core in terms of speed and memory, using different techniques such as reduced instruction computing, thread divergence and memory optimizations. Read the Report.pdf for detailed report on optimization performance result


<h2>How to compile the project</h2>
1. Copy the files to a local directory and set that directory as the current working directory.
2. Enter command "make filename" and replace the filename with the appropriate name of the file. For eg: make norm
3. Enter command "time ./filename" and replace the filename with the appropriate name of the file. For eg: time ./opt1

<h2>Files in the project</h2>
1. norm.cu contains the original code given by the the professor
2. opt1.cu deals with the category 4 where we need to do reduce the number of instructions a thread needs to do.
3. opt2.cu also deals with the category 4 by reducing the duplicate computation done by threads in a block
4. opt3.cu deals with category 2 i.e minimizing the thread diversion.
5. optAll.cu combines all the three optimization techniques used in opt1 , opt2 and opt3 
