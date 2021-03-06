---
title: Dr Paul Richmond - COM4521 & COM 6521 Introduction to Parallel Computing with GPUs 2017
layout: homepage
---

# About the Course

Accelerator architectures are discrete processing units which supplement a base processor with the objective of providing advanced performance at lower energy cost. Performance is gained by a design which favours a high number of parallel compute cores at the expense of imposing significant software challenges. This module looks at accelerated computing from multi-core CPUs to GPU accelerators with many TFlops of theoretical performance. The module will give insight into how to write high performance code with specific emphasis on GPU programming with NVIDIA CUDA GPUs. A key aspect of the module will be understanding what the implications of program code are on the underlying hardware so that it can be optimised.
 
The modules aims, objectives and assessment details are available on the [modules public teaching page](http://www.dcs.shef.ac.uk/intranet/teaching/public/modules/level4/com4521.html).


# Assessment

## Assignment

The assignment makes up 80% of the total marks for this module and is split into two related parts. The handout will be available on MOLE from week 3 and week 6 and will be handed in in two stages.  

* Part 1 is due Tuesday 28th March (5pm) - Week 8
* Part 2 is due Wednesday 16th May (5pm) -  Week 12.

## MOLE Quizes

Two quizes, each 10% of the module mark will be held under exam conditions on 

* Monday the 6th March (16:00-17:00) - Week 5 (This is during the second half of the lecture in Diamond High Spec Lab (DIA-206))
* Tuesday the 25th April (9:00-10:00) - Week 9 (This will take place during normal lab hours)


# Lecture Notes

Lectures will take place on Mondays 15:00 until 17:00 in Diamond lecture theatre DIA-LT09. In week 5 the second half of the lecture will be a MOLE quiz. Week 11 will be an invited lecture.

## Week 01: 

#### Lecture 01 - Introduction ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMSzlYdVJ4WFFaUjQ/view?usp=sharing))

* Context and Hardware Trends
* Supercomputing
* Software and Parallel Computing
* Course Outline


#### Lecture 02 - Introduction to C ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMd2NkM2txQ2tJVlE/view?usp=sharing))

* Introduction to the C Programming Language
* Basic C Usage "Hello World"
* Functions and Scoping
* Arrays, Strings and Basic IO
* File IO

#### Additional Notes on Visual Studio ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMMW1ZY1Q0Q2MzY2M/view?usp=sharing))

* Visual Studio 2013 Overview

## Week 02: 

#### Lecture 03 - Memory ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMMzZ4U2doNUhDT2M/view?usp=sharing))

* Pointers
* Advanced use of Pointers
* Dynamically Managed Memory
* Structures
* Binary Files

#### Lecture 04 - Optimisation ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMSm8xYXk1YUViUk0/view?usp=sharing))

* Optimisation Overview
* Compute Bound Code
* Memory Bound Code

#### NSS - National Stduent Survey ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMRDFBSFRLaDJtUlk/view?usp=sharing))

## Week 03: 

#### Lecture 05 - OpenMP ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMYXphNGVqaW1vSDA/view?usp=sharing))

* Multi-core Systems and OpenMP
* Parallelising Loops
* Critical Sections and Synchronisation
* OpenMP Scoping
* Task Parallelism with Sections

#### Lecture 06 - OpenMP Part II ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMSkFQMmNJM2NQSW8/view?usp=sharing))

* Parallel Reduction
* Scheduling
* Nesting

## Week 04: 

#### Lecture 07 - GPU Architectures ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMNDNQd2FfeXM0a0E/view?usp=sharing))

* What is a GPU?
* General Purpose Computation on GPUs (and GPU History)
* GPU CUDA Hardware Model
* Accelerated Systems

#### Lecture 08 - Introduction to CUDA ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMTkZ6YUdEVUZPY00/view?usp=sharing))

* CUDA Programming Model
* CUDA Device Code
* CUDA Host Code and Memory Management
* CUDA Compilation and execution in Visual Studio

## Week 05: 

#### Lecture 09 - CUDA Memory ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMLWRpSmpGVkkwWlk/view?usp=sharing))

* Memory Hierarchy Overview
* Global Memory
* Constant Memory
* Texture and Read-only Memory
* Roundup & Performance Timing

#### MOLE QUIZ

## Week 06: 

#### Lecture 10 - CUDA Shared Memory ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMY3ZtWWJKU3lzM28/view?usp=sharing))

* Shared Memory
* Shared Memory Bank Conflicts
* 2D Shared Memory Bank Conflicts
* Boundary Conditions for Shared Memory Loading
* Host-side Configurations for Shared Memory
* [Shared Memory Bank Conflict Calculator](https://drive.google.com/file/d/0B2HbOiEppVPMY3NteVJXMUwyazA/view?usp=sharing)

#### Lecture 11 - CUDA Performance ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMaXBPZGEzel9pakk/view?usp=sharing))

* Global Memory Coalescing
* Global Memory Coalescing with the L1 Cache
* Occupancy and Thread Block Dimensions

## Week 07: 

#### Lecture 12 - Warp Level CUDA ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMYkE5dFpGdnA1X00/view?usp=sharing))

* Warp Scheduling and Divergence
* Atomics
* Warp Operations

#### Lecture 13 - Parallel Patterns ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMQVZzX1RhVkozUTg/view?usp=sharing))

* Parallel Patterns Overview
* Reduction
* Scan
* [Shared Memory Bank Conflicts for Examples](https://drive.google.com/file/d/0B2HbOiEppVPMX0xHQ2l1d05GX3c/view?usp=sharing)

## Week 08: 

#### Lecture 14 - Sorting and Libraries ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMYUxCZnhodDlHZWc/view?usp=sharing))

* Sorting Networks
* Merge and Bitonic Sort
* Thrust Parallel Primitives Library
* Applications of Sorting (binning)

#### Lecture 15 - CUDA Streams ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMaXNpRFZ0TWNjYnM/view?usp=sharing))

* Synchronous and Asynchronous execution 
* CUDA Streams
* Synchronisation
* Multi GPU Programming

## Easter Vacation

## Week 09: 

#### Lecture 16 and 17 - Performance Optimisation ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMcW5oSEtNMzZJeTA/view?usp=sharing))

* Profiling Introduction
* The Problem
* Visual Profiler Guided Analysis
* Profiling in the lab Notes ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMdjFid0xsd0xuMFU/view?usp=sharing))

## Week 10: BANK HOLIDAY 

## Week 11: Invited Talk

## Week 12: NO LECTURE

# Labs

Labs will take place on Tuesdays 9:00 until 10:50 in the Diamond High Spec Lab (DIA-206). Week 9 lab will be a MOLE quiz followed by assignment help. Week 11 (full lab) will be for assignment help. Assignment help will also be availble during any of the normal lab sessions. There will be no lab in week 12.

A [Lab FAQ document](https://docs.google.com/a/sheffield.ac.uk/document/d/1w4k87mKyJke4bfbWbUVT7rpio2hN7_RUXRDZIT93j9g/edit?usp=sharing) has been prepared with common questions. This will be continually updated throughout the course.

## Lab Register ##

The lab register **must** be completed by every student following the completion and review of the exercises. You should complete this only when you have completed the lab **and** reviewed the solutions. You are not expected to complete this during the lab class but you should complete it by the end of the teaching week.

Lab Register Link: [https://goo.gl/0r73gD](https://goo.gl/0r73gD)


#### Getting started with the DGX-1 - Self Paced Lab ####

As part of the department of computer science you have the opportunity to access the DGX-1 GPU system with state or the art P100 GPUs. In order to access this system I have written a handy user guide / self paced getting started lab which describes the process specifically for this module. As part of this you will need to register for a HPC account.

[Getting started with the DGX-1 - Self Paced Lab](.\sharc)

*Note: It is not a requirement of the module to use this system (there are GPUs you can use in the diamond lab). This is offered as an additional opportunity to test your code on the very latest hardware. It is also possible to use the ShARC system remotely allowing you the added benefit of being able to work outside of the lab on your assignment.*

Assistance for this is self paced lab is available during any normal lab session. If there is sufficient interest I will put on an additional lab session for help with this.

If you are unfamiliar with Linux and the bash shell then this is probably not for you.....


#### Lab 01 - C Programming 

* Lab Sheet ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMUHp1N19RRlNZN3c/view?usp=sharing))
* Source Code ([zip](https://github.com/mondus/com4521/archive/Lab01_src.zip))
* Solution ([zip](https://github.com/mondus/com4521/archive/Lab01_sln.zip))

#### Lab 02 - Memory and Performance

* Lab Sheet  ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMMVhrQlZXLUNHTjQ/view?usp=sharing))
* Source Code ([zip](https://github.com/mondus/com4521/archive/Lab02_src.zip))
* Solution ([zip](https://github.com/mondus/com4521/archive/Lab02_sln.zip))

#### Lab 03 - OpenMP

* Lab Sheet ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMRmZtc0RVd2ZwcDA/view?usp=sharing))
* Source Code ([zip](https://github.com/mondus/com4521/archive/Lab03_src.zip))
* Solution ([zip](https://github.com/mondus/com4521/archive/Lab03_sln.zip))

#### Lab 04 - Introduction to CUDA

* Lab Sheet ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMUkt1NDRQMXYwVnc/view?usp=sharing))
* Source Code ([zip](https://github.com/mondus/com4521/archive/Lab04_src.zip))
* Solution ([zip](https://github.com/mondus/com4521/archive/Lab04_sln.zip))

#### Lab 05 - Memory

* Lab Sheet ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMTXJwM0VWWjVzNEE/view?usp=sharing))
* Source Code ([zip](https://github.com/mondus/com4521/archive/Lab05_src.zip))
* Solution ([zip](https://github.com/mondus/com4521/archive/Lab05_sln.zip))

#### Lab 06 - Shared Memory and Occupancy

* Lab Sheet ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMazRDUTJsa0xFVlk/view?usp=sharing))
* Source Code ([zip](https://github.com/mondus/com4521/archive/Lab06_src.zip))
* Solution ([zip](https://github.com/mondus/com4521/archive/Lab06_sln.zip))
 
#### Lab 07 - Atomics and Primitives

* Lab Sheet ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMTjI4aTVBekZYVmc/view?usp=sharing))
* Source Code ([zip](https://github.com/mondus/com4521/archive/Lab07_src.zip))
* Solution ([zip](https://github.com/mondus/com4521/archive/Lab07_sln.zip))

#### Lab 08 - Libraries and Streams

* Lab Sheet ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMbFIxUjdrUTkyOFE/view?usp=sharing))
* Source Code ([zip](https://github.com/mondus/com4521/archive/Lab08_src.zip))
* Solution ([zip](https://github.com/mondus/com4521/archive/Lab08_sln.zip))

#### Lab 09 - MOLE QUIZ 2,  Profiling and Assignment Help

* Assignment help
* Profiling your own code in the Diamond Lab Notes ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMdjFid0xsd0xuMFU/view?usp=sharing))
* Solution code and profiles ([zip](https://github.com/mondus/com4521/archive/lab09_sln.zip))

#### Lab 10 - CUDA OpenGL Interop

* Lab Sheet ([pdf](https://drive.google.com/file/d/0B2HbOiEppVPMemp6eEtXdzExX0k/view?usp=sharing))
* Source Code ([zip](https://github.com/mondus/com4521/archive/lab09_sln.zip))
* Solution

#### Lab 11 - Profiling and Assignment Help

* Assignment help
* Profiling your own code in the Diamond Lab

# Discussion, Announcements and Help

Discussion, announcements and help requests (outside of the labs) should be made via the modules public Gooogle Group.

[https://groups.google.com/a/sheffield.ac.uk/d/forum/com4521-group](https://groups.google.com/a/sheffield.ac.uk/d/forum/com4521-group)

# Calendar

You can add this calendar to your University of Sheffield Google Calendar by searching for COM4521 and COM6521

<iframe src="https://calendar.google.com/calendar/embed?src=sheffield.ac.uk_4gq0ug3uf8dlts9d21gp4l1des%40group.calendar.google.com&ctz=Europe/London" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>

# Recommended Reading

* Edward Kandrot, Jason Sanders, "CUDA by Example: An Introduction to General-Purpose GPU Programming", Addison Wesley 2010.
* Brian Kernighan, Dennis Ritchie, “The C Programming Language (2nd Edition)”, Prentice Hall 1988.
* NVIDIA, [CUDA C Programming Guide](http://docs.nvidia.com/cuda/cuda-c-programming-guide/)
