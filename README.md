# COVID TRACING PROJECT

This is a project which is a scaled down version of contact tracing and application of graphs in real life.This project has been made entirely in C and can basically perform certain queries regarding conditions of people when given a list of infected people and also can give the most safest path that should be taken in order to minimize chances of contracting the Virus.

## Installation

Just gitclone/Download the project repo and run using gcc

```bash
git clone https://github.com/TheAthleticCoder/IIITH-PROJ
gcc main.c
./a.out
```
## Index

### 1.extra.c and extra.h
Contain generic functions for implementations of linked lists ,stacks and queues which are used in subsequently.
### 2.graph.c and graph.h
Contains functions for implementations of graphs and Dijkstra's and safety values concept which is crucial for solving part 2 of the question.
### 3.personll.c and personll.h
Contains functions and structures for storing and querying data regarding people and stations.
### 4.lists.c
Contains some utility functions which help in calculation of part1.
### 5.MIni_Project.pdf
Contains the question statement we are aiming to solve (question 6).

## Usage

```
(example inputs)
Enter number of stations,roads and people //it is exactly as it asks...requires numerical input.
7 9 14 
Enter names of the station: //requires alphabetic names
a b c d e f g
Enter the bidirectional paths: //enter graphs from point a to point b with weight w as a b w.
1 2 10
1 3 20
3 7 60
2 7 50
7 4 20
7 6 30
6 5 80
6 1 90
3 5 100
Enter station number of each person:Enter the source station of 1 //enter the index of person whom do you want to place in station x as x...loop till people
1
Enter the source station of 2
2
Enter the source station of 3
3
Enter the source station of 4
4
Enter the source station of 5
5
Enter the source station of 6
6
Enter the source station of 7
7
Enter the source station of 8
1
Enter the source station of 9
2
Enter the source station of 10
3
Enter the source station of 11
4
Enter the source station of 12
5
Enter the source station of 13
6
Enter the source station of 14
7
For Day: 1, Enter the Query number //enter alphabets A for giving list of covid +ve people,B for calculating 3 shortest paths and safest paths between a and b
,C for making a person travel, D for incrementing a day, E to query stations and F for individual queries.
Enter the required values asked corresponding to the function chosen.
```
## Assumptions
1. Primary and Secondary Contacts are reset after everyday.(If you are a primary contact on one day, the next day you become neutral)
2. The Covid positive person after 15 days becomes neutral.
3. Since there has been no limit on the number of days or regarding th people and stations, the maximum limit is hard coded to 100.(which can be changed).

## Contributing
This has been made solely by 3 people [Harshit Gupta](https://github.com/TheAthleticCoder "Harshit Gupta") ,[ N Harsha V](https://github.com/harsha20032020 "N Harsha Vardhan")  and [Rohan V M](https://github.com/rohanmodepalle "Rohan Modepalle") .
Although this is a course project , any ways to optimize the code and algorithms/data structures used in the program are welcomed for a discussion and maybe you can create a pull request.

## License
[MIT](https://choosealicense.com/licenses/mit/)
