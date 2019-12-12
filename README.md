# Bankers Algorithm
Bankers Algorithm implemented in Python 3 with a Flask REST backend and an HTML/Bootstrap/JS front end.
The front end is hosted on Heroku at http://bankers.alexday.me. 

## Usage
This was a project for the Operating Systems class at Clarion. This project had a specific input file format
that is shown on the left hand side of the web app. This format is also shown with comments describing what 
each line corresponds to below.

```C
5       // Number of processes    
3       // Number of resources
10 5 7  // Maximum resource allocation
0 1 0   // Currently allocated for proc 1
2 0 0   // Currently allocated for proc 2
3 0 2   // Currently allocated for proc 3
2 1 1   // Currently allocated for proc 4
0 0 2   // Currently allocated for proc 5
7 5 3   // Max allocated for proc 1
3 2 2   // Max allocated for proc 2
9 0 2   // Max allocated for proc 3
2 2 2   // Max allocated for proc 4
4 3 3   // Max allocated for proc 5
```

This is the default configuration used on the first launch of the application. The right hand side is used to
make resource requests and also to check the validity of the current system configuration. 
