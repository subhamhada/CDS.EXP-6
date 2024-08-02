# Experiment-6
## Aim -
To study and implement C++ decision making statement loops
## Theory -
Loops are used to make the program less repetitive and compact ny iterating a part of a program several times .Thus,they are also  called repetitive control structures.

Types of loops:-
a) *for loop*

b) *while/do-while loop*

### For Loop -
 A "for" loop is a control flow statement used to repeat a block of code a certain number of times. 
 
 The syntax can vary slightly depending on the programming language.

 ### While loop:-
 A "while" loop is another type of control flow statement that repeatedly executes a block of code as long as a specified condition is true. 

  You can control the flow inside a "while" loop using break to exit the loop and continue to skip to the next iteration:

 ### Do-while loop:-
It executes the block of code at least once before checking the condition. Python does not have a built-in "do-while" loop, but you can simulate it.

You can control the flow inside a "while" loop using break to exit the loop and continue to skip to the next iteration:

### Nested loops:-
Nested loops involve placing one loop inside another. They can be useful for handling multi-dimensional data or performing complex iterations.

Nested loops can be quite powerful but can also lead to performance issues if not used carefully, especially with large datasets or high iteration counts.

## Code:-

### 1. *For loop*
```
//subham
//23070123132
//entc B2
//experiment 6
#include<iostream>
using namespace std;
int main()
{
    int i;
    for(i=0;i<10;i++)
    {
        cout<<"heloo world("<<i+1<<")"<<endl;
    }
}
```

### 2. *while loop*
```
//subham
//23070123132
//entc B2
//experiment 6
#include<iostream>
using namespace std;
int main() 
{
    int input = 1;
    while (input <= 15) {
        std::cout << "\n" << input;
        input++;
    }
}
```

### 3. *Do-while*
```
//subham
//23070123132
//entc B2
//experiment 6
#include <iostream>

using namespace std;

int main() {
    int number = 1;
    do {
        cout << number << endl;
        number++;
    } while (number <= 10);
    return 0;
}
```

### 4. *Nested for loop*
```
//subham
//23070123132
//entc B2
//experiment 6
#include<iostream>
using namespace std;
int main() {
    for (int i = 1; i <= 1; i++) {
        for (int j = 1; j <= 10; j++) {
            std::cout << j << " ";
        }
    }
    std::cout << std::endl;
    return 0;
}
```

### 5. *Nested while*
```
//subham
//23070123132
//entc B2
//experiment 6
#include<iostream>
using namespace std;
int main()
{
    int i = 1;
    while (i <= 10) {
        int j = 1;
        while (j <= i) {
            std::cout << j << " ";
            j++;
        }
        std::cout << std::endl;
        i++;
    }
    return 0;
}
```

### 7. *Nested do while*
```
//subham
//23070123132
//entc B2
//experiment 6
#include<iostream>
using namespace std;
int main() {
    int i = 1;
    do {
        int j = 1;
        do {
            std::cout << j << " ";
            j++;
        } while (j <= 10);
        i++;
    } while (i <= 1);
    std::cout << std::endl;
    return 0;
}
```

### 7. *Nested for while*
```
//subham
//23070123132
//entc B2
//experiment 6
#include<iostream>
using namespace std;
int main()
{
    int i,j,k=0,n;
    cout<<"enter number of rows-";
    cin>>n;
    for(i=1;i<=n;i++)
    {
        for(j=1;j<=(n-i);j++)
        {
            cout<<" ";
        }
        while(k!=(i-1))
        {
            cout<<"* ";
            k++;
        }
        k=0;
        cout<<endl;
    }
    cout<<endl;
}
```
