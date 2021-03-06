# Course Syllabus

This is a detailed, week-by-week description of topics covered in the course. Here we will post the lecture content and lecture references as well the homework and quiz scheudles.

Weekly quizzes are designed to test your knowledge of the content of the previous week's lectures and the "Primary References" listed.

* Once you begin you will have **20 minutes** to complete the quiz.
* You have one attempt.
* If you want the full 20 minutes then begin the quiz 15 minutes before the end of the window.
* You cannot pause the quiz and resume at a later time, even within the window.
* Questions will be presented one at a time. Once you answer a question you cannot return to it.
* Quiz Window: **Sunday, 5:00pm PST - Tuesday, 5:00am PST**

Biweekly homework is automatically collected every other **Friday at 5:00pm PST**, no exceptions.
* Be sure your in-class git repository is updated with both your code and your written report.
* We will automatically clone your repos at 5:00pm PST.

## Week 1: 28 March - 1 April

* Tue: Course overview, syllabus, and goals. Setting up your compute environment. Introduction to Unix.
  * Primary Reference: [Linux Tutorial](http://ryanstutorials.net/linuxtutorial/) Sections 1,2,3,4,5,7
* Thu: Introduction to Git
  * Primary Reference: [Official Git Documentation](https://git-scm.com/doc) Chapters 1,2,3
  * Secondary References:
    * [Code School - Try Git](https://try.github.io/levels/1/challenges/1)
    * [Understanding GitHub Flow](https://guides.github.com/introduction/flow/)
    * [Hello World](https://guides.github.com/activities/hello-world/)
    * [Contributing to Open Source](https://guides.github.com/activities/contributing-to-open-source/)
    * [GitHub and Git Foundataions Training](https://www.youtube.com/playlist?list=PLg7s6cbtAD15G8lNyoaYDuKZSKyJrgwB-)
* **Additional Work** Learn Python
  * Primary Reference: [Official Python Tutorial](https://docs.python.org/2.7/tutorial/index.html) Sections 3,4,5,6,14
  * Secondary References:
    * [Codeacademy's Python Course](https://www.codecademy.com/learn/python)
    * [Learn Python the Hard Way](http://learnpythonthehardway.org/book/)

## Week 2: 4 April - 8 April

* **Quiz #1: Python, Unix, and Basic Git**
  * *Note: you will have 30 minutes to complete this quiz instead of the usual 15.*
* **Homework #1 Assigned**
* Tue: How to Homework, more on Git, Numpy and Matplotlib
  * Primary References:
    * [Numpy Quickstart Guide](https://docs.scipy.org/doc/numpy-dev/user/quickstart.html)
    * [Matplotlib Pyplot Tutorial](http://matplotlib.org/users/pyplot_tutorial.html)
  * Secondary References:
    * [Complete Numpy Reference Manual](http://docs.scipy.org/doc/numpy/reference/)
    * [Matplotlib Image Gallery](http://matplotlib.org/gallery.html) *(Click a picture and see how to make it.)*
    * [Why are numpy arrays so fast](http://stackoverflow.com/questions/8385602/why-are-numpy-arrays-so-fast) (*A stackoverflow question*)
* Thu: Basics of Computer Hardware and Arithmetic
  * Primary References:
    * [Memory Hierarchy](https://en.wikipedia.org/wiki/Memory_hierarchy)
    * [Stack Overflow: Where are the stack and heap](http://stackoverflow.com/questions/79923/what-and-where-are-the-stack-and-heap)
  * Secondary References:
    * [Latency Numbers Every Programmer Should Know](https://gist.github.com/jboner/2841832)
    * [The Call Stack](https://en.wikipedia.org/wiki/Call_stack)
    * [Floating point inaccuracy examples](http://stackoverflow.com/questions/2100490/floating-point-inaccuracy-examples)

## Week 3: 11 April - 15 April

* **Quiz #2: Numpy, Matplotlib, and Basics of Computer Hardware**
* Tue: C - Introduction, syntax
  * Primary Reference:
    *[Cprogramming.com - Introduction to C](http://www.cprogramming.com/tutorial/c/lesson1.html) *(see "Tutorial Map" on left side of page)* Lessons: Intro, If Statements, Loops, Functions, Pointers, Arrays, Typecasting
    * [Wiki - C Dynamic Memory Allocation](https://en.wikipedia.org/wiki/C_dynamic_memory_allocation)
  * Secondary References:
    * [Learn C the Hard Way](http://c.learncodethehardway.org/book/)
* Thu: C - Function, Arrays on the Stack and Heap
  * Primary Reference:
    * [Arrays in C](https://www.cs.swarthmore.edu/~newhall/unixhelp/C_arrays.html)
  * Secondary References:
    * [uwhpsc-2016/lectures#2](https://github.com/uwhpsc-2016/lectures/issues/2) - articles on how heap allocations are managed. Can be considered too deep for our purposes but interesting, nonetheless. Thinking in terms of memory locations.

## Week 4: 18 April - 22 April

* **Quiz #3: C**
* **Homework #2 Assigned**
* Tue: Multi-file C Programs
  * Primary Reference:
    * [Guide: Makefiles](http://www.delorie.com/djgpp/doc/ug/larger/makefiles.html) - there are many Makefile tutorials online. This one encompasses most of what you need to know for this class.
    * [Sage Tutorial: Ctypes](http://doc.sagemath.org/html/en/thematic_tutorials/numerical_sage/ctypes.html) - nice summary of ctypes with applications
  * Secondary Reference:
    * [GNU make](https://www.gnu.org/software/make/manual/make.html#Introduction) - a more in-depth (and official) guide to makefiles
* Thu: Performance Considerations - cache, optimization, measuring performance
  * Primary Reference:
    * * [Locality of Reference](https://en.wikipedia.org/wiki/Locality_of_reference) - Wikipedia,
  * Secondary References:
    * [What is Cache Friendly Code](http://stackoverflow.com/a/16699282/645494) - a great summary from SO,
    * [Three Optimization Tips for C++](https://www.facebook.com/notes/facebook-engineering/three-optimization-tips-for-c/10151361643253920) - from Facebook Engineering,
    * [What is Branch Predicition?](http://stackoverflow.com/a/11227902/645494) - excellent SO response,

## Week 5: 25 April - 29 April

* **Quiz #4: Performance Considerations**
* **Homework #1 Due**
* Tue: Introduction to parallel programming concepts and OpenMP
  * Primary Reference:
    * [Thread (wikipedia)](https://en.wikipedia.org/wiki/Thread_(computing)) - dense, but at least read sections 1,2,3,4
  * Secondary Reference:
    * [POSIX Threads (wikipedia)](https://en.wikipedia.org/wiki/POSIX_Threads) - example of the kind of code that OpenMP and MPI generate
* Thu: OpenMP
  * Primary Reference:
    * [OpenMP](https://computing.llnl.gov/tutorials/openMP/) - read through "Work-Sharing Constructs DO / for Directive", about 1/3 down the page. Reads more like a reference but has very useful information.
  * Secondary Reference:
    * [Intro. to OpenMP - Tim Mattson](https://www.youtube.com/playlist?list=PLLX-Q6B8xqZ8n8bwjGdzBJ25X2utwnoEG) - nice collection of YouTube videos from Intel. Talks about parallelism from a very basic perspective. The slower pace is good if you're having trouble wrapping your head around parallelism.

## Week 6: 2 May - 6 May

* **Quiz #5: Parallel Programming and OpenMP Basics**
* Tue: More on OpenMP
  * Primary Reference:
    * [OpenMP](https://computing.llnl.gov/tutorials/openMP/) - *read the following sections:* SECTIONS Directive, Synchronization Constructs (just after "OpenMP Exercise 2"), MASTER Directive, CRITICAL Directive, BARRIER Directive, ATOMIC Directive, REDUCTION Clause (later in the document)
  * Secondary Reference:
    * [Difference between `omp critical` and `omp atomic`](http://stackoverflow.com/a/7798994/645494) - A Stackoverflow response discussing the performance differences between critical regions and atomics
    * [A cache miss is not a cache miss](http://larshagencpp.github.io/blog/2016/05/01/a-cache-miss-is-not-a-cache-miss) - an article I came across over the weekend about cache misses. Not necessarily about OpenMP, nor actually about C, (the author uses C++) but nonetheless interesting. A light C++ background might be needed to understand what's going on.
* Thu: Running Example - Estimating Pi
  * Primary Reference:
    * [32 OpenMP Traps for C++ Developers](http://www.viva64.com/en/a/0054/) - although the title mentions C++ nearly all of the code examples do not use the features of C++. You do not need to read the items on OpenMP functions that we haven't talked about in class (e.g. `flush`, `ordered`, info about locks) but you may be interested, nonetheless.
  * Secondary Reference:
    * [Wiki - False Sharing](https://en.wikipedia.org/wiki/False_sharing)
    * [Wiki - Cache Coherency](https://en.wikipedia.org/wiki/Cache_coherence) - particularly, the article on [bus sniffing / snooping](https://en.wikipedia.org/wiki/Bus_sniffing) is a common implementation of cache coherence
* **Homework #3 Assigned**
* **Fri: Homework #2 Due @ 5:00pm**

## Week 7: 9 May - 13 May

* **Quiz #6: OpenMP**
* Tue: Introduction to MPI
* Thu: More on MPI
  * Primary Reference:
    * [MPI Tutorial](http://mpitutorial.com/tutorials/) - a nice tutorial on the basic and key types of operations in MPI.
  * Secondary References:
    * [MPI Standard](http://www.mpi-forum.org/docs/mpi-3.1/mpi31-report/mpi31-report.htm) - the reference guide to the MPI 3.1 standard. does not read like a tutorial but is comprehensive.
    * [MPI's Send Modes](http://www.mcs.anl.gov/research/projects/mpi/sendmode.html) - default, guaranteed blocking, and non-blocking versions of `MPI_Send`.
    * [Difference between `MPI_Send` and `MPI_Ssend`](http://stackoverflow.com/a/17593678/645494) - pretty good SO repsonse on differences.

## Week 8: 16 May - 20 May

* **Quiz #7: MPI**
* Tue: Advanced Point-to-Point Commuinication
  * Primary Reference:
  * Secondary Reference:
    * [Writing Paralell Libraries with MPI](http://htor.inf.ethz.ch/publications/img/hoefler-mpi-libraries.pdf) - an interesting summary article on techniques for writing shared object libraries that run on MPI.
* Thu: (Cancelled)
* **Homework #4 Assigned**
* **Fri: Homework #3 Due @ 5:00pm**

## Week 9: 23 May - 27 May

* **Quiz #8: Advanced MPI and Parallelism Performance Concerns**
* Tue: Adaptive Quadrature, Recursion, and Load Balancing
  * Primary Reference:
    * [OpenMP Sections](https://computing.llnl.gov/tutorials/openMP/#SECTIONS)
    * [Running MPI Jobs](https://www.open-mpi.org/faq/?category=running#mpirun-specify-hosts) - guide on running MPI code, such as on remote machines.
  * Secondary Reference:
    * [Nested Parallelism](https://docs.oracle.com/cd/E19059-01/stud.10/819-0501/2_nested.html)
* Thu: *Guest Lecture by Daniel Shapero* Sparse Matrices
  * Primary Reference:

## Week 10: 30 May - 3 June

* Tue: CUDA and GPU Programming - Part 1
* Thu: CUDA and GPU Programming - Part 2
  * [CUDA Quickstart Guide](http://developer.download.nvidia.com/compute/cuda/7.5/Prod/docs/sidebar/CUDA_Quick_Start_Guide.pdf) - how to get CUDA installed and configured on your system. (WIN/OSX/LINUX)
  * [CUDA Programming Guide](http://docs.nvidia.com/cuda/pdf/CUDA_C_Programming_Guide.pdf) - nearly everything you need to know about writing CUDA code. 
  * [CUDA Toolkit Documentation](http://docs.nvidia.com/cuda/index.html#axzz48mypHkfM) - collection of guides and documentation for CUDA related things. Includes the two guides above.
  * [CUDA by Example](https://developer.nvidia.com/cuda-example) - an excellent book for getting started with CUDA programming. As the title implies, there are many good examples throughout the book.
* **Fri: Homework #4 Due @ 5:00pm**

## Final Exam

Tuesday, 7 June 2016 <br />
1030am - 1220pm <br />
SMI 205

# Parting Words of Wisdom

A collection of suggested reading related to what we have learned in this class. It has been a challenging and fun quarter!

* [What Every Programmer Should Know About Memory](https://people.freebsd.org/~lstewart/articles/cpumemory.pdf) - Considered by many a must read, even though it is about seven years old now.
* [Deopimizing a C++ Program](http://stackoverflow.com/q/37361145/645494) - One can learn about how to optimize a program by learning how to make things as bad as possible. The author of the [top answer](http://stackoverflow.com/a/37362225/645494) has some deep insight on Sandybridge architecture.
* [Unmaintainable Code](https://www.thc.org/root/phun/unmaintain.html) - How to secure your job by writing code such that it is nearly impossible for someone else to contribute to it.
* [The Green Place - Eli Bendersky's Website](http://eli.thegreenplace.net) - Bendersky is a Googler whose programming insights are pretty incredible. I'm always fascinated with his posts which usually set me on a Wiki/Google path for the rest of the dat.
* [Stutter's Mill](https://herbsutter.com) - Herb Stutter is a software architecht at Microsoft who has been foundational in the recent updates to the C++ programming language. His blog, though mostly on developments in the language, contants some very insightful posts about C++ internals.
* [The Story of Mel](http://www.catb.org/jargon/html/story-of-mel.html) - Learn what it was like to be a "Real Programmer".
