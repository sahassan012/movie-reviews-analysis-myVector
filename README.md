# myVector
## About

The built-in C++ Vector class from the standard library is based on a dynamically-allocated array. This repo consists of a new implementation of the vector class, using a different design approach.

## How it works
The Movie Reviews program within functions.cpp uses .txt files that consist of movie reviews as a way of testing and utilizing the new vector class(myVector).

The .txt file expected by the program must be in the following format:
* line 1: Movie name
* All lines after: 1-5 (ratings)
* last line: -1 (terminating character)

## How to run program in shell
From the project directory execute:\
```./a.out```\
and then enter the .txt file name:\
```movie1.txt``` 

Output:
```console
Movie: Finding Nemo
Num reviews: 5
Avg review:  4.6
5 stars: 3
4 stars: 2
3 stars: 0
2 stars: 0
1 star:  0
```
