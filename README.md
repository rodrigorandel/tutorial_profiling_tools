# Tutorial, Hints and Good Practices on Profiling Tools

## Motivation
  In a nutshell, code profiling tools perform dynamic analysis to **gathers richness information** about the program, allowing developers to **optimize their codes**. The tutorial aims to demonstrate how to utilize profiling tools and enhance algorithms regarding the following aspects:
1. Execution time
    - Computing the **program's complexity**
    - Identify the algorithm's **bottlenecks**
    - Analyzing the **numbers of calls and time spent in each instruction**
2. Memory Usage
    - Studying the 
    **space complexity**
    - Identifying **overhead due to allocations**
    - Optimizing the **cache efficiency**
3. Help to prevent bugs

## Possible outline for the tutorial (should be adapted to match the attendees' need)
1. Introduction to *Profiling tools*
    - Motivation with examples to demonstrate the importance and benefits of profiling a program.
    - Introduction to the main concepts and information that can be obtained
2. Present two of the most well-known profiling tools:
    - **Valgrind** for *C/C++* 
      - Important note: this tutorial was presented at GERAD and all details, including the presentation file and examples' source codes, can be found on [https://github.com/rodrigorandel/introduction_to_valgrind] (https://github.com/rodrigorandel/introduction_to_valgrind) 
    - **profile and cProfile** for *Python*
3. Good practices to execute and interpret a profiling tool
4. Profiling for a distributed system and parallel programming
5. Final remarks
