
<a name="readme-top"></a>

<!-- PROJECT SUMMARY -->
<div align="center">

<h3 align="center">push_swap</h3>

  <p align="center">
    Summary:
    This project is an introduction to algorithms, choosing the most appropriate and to the stack data type.
    <br>
  </p>
</div>

<!-- TABLE OF CONTENTS -->

- [About The Project](#about-the-project)
- [Usage](#usage)
- [Sources](#sources)

<!-- ABOUT THE PROJECT -->
## About The Project

The goal of the project is to sort data on a stack using the lowest possible number of actions.

To do that we have some instructions to manipulate the two stacks that we are allowed to use:
* ```pa``` (push A): Take the first element at the top of B and put it at the top of A. Do nothing if B is empty.
* ```pb``` (push B): Take the first element at the top of A and put it at the top of B. Do nothing if A is empty.
* ```sa``` (swap A): Swap the first 2 elements at the top of stack A. Do nothing if there is only one or no elements.
* ```sb``` (swap B): Swap the first 2 elements at the top of stack B. Do nothing if there is only one or no elements.
* ```ss```: ```sa``` and ```sb``` at the same time.
* ```ra``` (rotate A): Shift all elements of stack A up by 1. The first element becomes the last one.
* ```rb``` (rotate B): Shift all elements of stack B up by 1. The first element becomes the last one.
* ```rr```: ```ra``` and ```rb``` at the same time.
* ```rra``` (reverse rotate A): Shift all elements of stack A down by 1. The last element becomes the first one.
* ```rrb``` (reverse rotate B): Shift all elements of stack b down by 1. The last element becomes the first one.
* ```rrr``` : ```rra``` and ```rrb``` at the same time.

It must be coded in C.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE -->
## Usage

After cloning the repo and getting into the folder, compile it with `make`.

Run it with:

```shell
./push_swap <numbers>
```

The numbers provided can be positive or negative integers. There must not be any duplicates and you can put them in doubles quotes `""`.

The program can be checked with the provided checker obtained from `checker.c`, like this :

```shell
ARG="3 0 9 2 -1"; ./push_swap $ARG | ./checker $ARG
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SOURCES -->
## Sources

* Radix Sort:
  * https://www.tutorialspoint.com/c-program-for-radix-sort
  * https://www.programiz.com/dsa/radix-sort
  * https://www.geeksforgeeks.org/radix-sort/
  * https://www.javatpoint.com/radix-sort
  * https://github.com/HSatwick/ProgrammersCorner/tree/master/RadixSortLinkedList
  * https://medium.com/nerd-for-tech/push-swap-tutorial-fa746e6aba1e
  * https://www.youtube.com/watch?v=Ic7SkpmXAOo radixsort with linked list

* Counting Sort:
  * https://www.geeksforgeeks.org/counting-sort/
  * https://www.javatpoint.com/counting-sort

* Merge Sort:
  * https://www.geeksforgeeks.org/merge-sort-for-linked-list/

<p align="right">(<a href="#readme-top">back to top</a>)</p>
