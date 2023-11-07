## Week 11 <br>Week of 11/6

### [Unit 2](/apcsp/curriculum/2)

  |       |In Class               |Homework   |
  |-------|---------              |---------  |
  |**Mon**|Merge Sort |[Lab for this unit](https://cs50.harvard.edu/ap/2024/curriculum/x/labs/3/) |
  |**Tue**|Cover how to swap values in calss, then do Bubble Sort Practice below | |
  |**Wed**|Start on [Practice Problems](https://cs50.harvard.edu/ap/2024/problems/3/) | |
  |**Thu**| | |
  |**Fri**| | |


<meta http-equiv="refresh" content="300"/>

<img src="https://i.pinimg.com/originals/de/f5/2f/def52fe41d695d8feebd2cdc194da929.png" alt="programming is easy;" height="350">

#### Bubble Sort Practice
- Write a program `bubble.c` that sorts an array of integers using bubble sort.
- Distribution Code:

```c
#include <cs50.h>
#include <stdio.h>

int main(void)
{
    // Get input
    int n = get_int("How many values? ");
    int values[n];
    for (int i = 0; i < n; i++)
    {
        values[i] = get_int("Value %i: ", i);
    }

    // TODO: sort numbers

    // Print sorted values
    for (int i = 0; i < n; i++)
    {
        printf("%i\n", values[i]);
    }
}
```