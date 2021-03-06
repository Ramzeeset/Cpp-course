# C++ course practices

**Intrusive List (C++)**

An intrusive List is a container that is a doubly linked list. Unlike std :: list, it does not make copies of the elements inserted into the list, but builds a list of those objects that are passed to it in insert, push_front and push_back.

You can add objects not of any type to intrusive :: list, but only those that inherit from intrusive :: list_element <Tag>

**LFRU-MULTI-TYPE Allocator (C++)**

The cache is divided into two areas: privileged and non-privileged. The privileged one is modeled as an LRU list, and the non-privileged one is modeled as a FIFO queue.

**Shared Pointer (C++)**
  
Shared_ptr is a smart pointer that retains shared ownership of an object through a pointer. Several shared_ptr objects may own the same object.   

**Function (C++)**
  
Implemented analog of standard function with small object  optimisation. 
  
**Integral Calculation Lib (C++)**

Small lib for calculation integrals of the second kind and curvilinear integrals. Implemented simple multithreading to make program faster.
