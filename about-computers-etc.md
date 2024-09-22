# About Computing Parts and Concepts

## CPU
Central Processing Unit (processor)
- acts as the brain of the CPU
- Usually has around 4-8 cores (processors)
  - Minimum of 1-core, consumer computers are currently capped at 64-core, there is no actual limit
- Has a few-dozen threads (usually 2 threads per core)
- good for serial processing

  **Serial Processing**: Tasks executed in a specific, linear order, with each instruction dependant on the previous
- e.g. Intel Core, AMD Ryzen, etc.


## GPU
Graphics Processing Unit
- mainly a **processor** for graphics, currently able to process a variety of applications
- has thousands of threads
- good for parallel processing
  
  **Parallel Processing**: Tasks are completed concurrently
- e.g. NVIDIA GeForce, AMD Radeon, etc.



## Core / Processor
A physical hardware unit
- Each core independantly executes one task at a time
- A core can simulate parallel processing by quickly switching between multiple threads (not actually parallel)

## Threading
A thread is a single software unit of execution, running as a component in a process
-  **multithreading** is the simultaneous execution of multiple threads within a process
-  multithreading allows true parallel processing

## Serialization
The proccess of converting a data structure or object state into a reconstructable byte stream for storing or transmitting
- e.g. YAML, JSON, CSV, XML, etc.
- [[Wikipedia] Comparison of data-serialization formats](https://en.wikipedia.org/wiki/Comparison_of_data-serialization_formats)


## Kernel

## Application Layer
