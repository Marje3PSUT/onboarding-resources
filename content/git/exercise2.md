+++
title = 'Exercise 2'
date = 2024-07-18T18:42:06+03:00
draft = false
+++

#### Create a folder with the name "assignment2" with the following files
```
.
├── main.c
└── README.md
```
```c
// main.c should include the following

#include <iostream>
using namespace std;

int main(){
  cout << "yet another assignment!" << endl;
  return 0;
}
```

1. Initialize a new repository.

2. Create a seperate devv branch, checkout into it and add the following the README.md file:

```md
# Assignment 2

This is a markdown file.
```

3. Go back to the main branch and modify the program to print "I have to solve yet another assignment!"

> Wait, isn't this question almost identical to the first one?

4. Rebase the devv branch on the main branch.

5. Merge the main branch with the devv branch  and delete the devv branch.

> Try sketching each commit in a tree structure, that will surely help you understand the difference. `git log` helps too.