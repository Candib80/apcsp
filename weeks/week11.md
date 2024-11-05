## Week 11 <br>Week of 11/4

### [Unit 2](/apcsp/curriculum/2)

  |       |In Class               |Homework   |
  |-------|---------              |---------  |
  |**Mon**|Work on PSETs |If you are working on the EC problems for Unit 2, see Bubble Sort Practice below<br>You may also want to see me about how to swap values if you can't figure it out on your own |
  |**Tue**|Check that practice problems are done<br>Continue working on PSETs |Continue working on PSETs |
  |**Wed**|Continue working on PSETs<br>They are due tomorrow<br>Test will be next Tuesday |Continue working on PSETs |
  |**Thu**| | |
  |**Fri**|Write Runoff together in class<br>Test next Tuesday, review on Monday | |


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