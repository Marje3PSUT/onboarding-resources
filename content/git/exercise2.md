+++
title = 'Exercise 2'
date = 2024-07-18T18:42:06+03:00
draft = false
+++

#### Create a folder with the name `assignment1` with the following files:

```
.
├── main.c
├── my_notes.txt
└── README.md
```

```c
// main.c should contain the following

#include <iostream>
using namespace std;

int main() {
  cout << "Hello world!" << endl
  return 0
}
```

> Try compiling the code... Something isn't right, isn't it?

1. Initialize a new repository with a main branch and ensure that the my_notes.txt file is not tracked in the repository.

<details>
<summary>Hint</summary>
<div>
Maybe you should create a .gitignore file.
</div>
</details>

2. Create a seperate devv branch, move into it and apply the necessary changes to the main.c file for it to compile.

<details>
<summary>Hint</summary>
<div>
This step involves quite a few commands to run after you've applied your changes. are you well versed?
</div>
</details>

3. Go back to the main  branch and add the following line of code before the program prints its message:  int x = 47; 

4. Merge the devv branch into the main branch and delete the devv branch.

> Try running `git log. VSCode and other code editors provide a super useful interface for git, consider trying them out!
