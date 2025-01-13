## Week 18 <br>Week of 1/13

[Create](/apcsp/curriculum/pt/create) - Due to me, marked as FINAL in Digital Portfolio, Feb. 28

  |       |In Class               |Homework   |
  |-------|---------              |---------  |
  |**Mon**|Go over Narrow it Down |Complete the function practice problem below and screenshot your code and upload to Canvas Assignment<br>Make sure you feel as if you can program your idea |
  |**Tue**|Collaborate with your classmates and ask Ms. Beaman about your idea before you start writing it |Work on Create |
  |**Wed**|Work on Create D1 |Work on Create |
  |**Thu**|Work on Create D2 |Work on Create |
  |**Fri**|Work on Create D3 |Create Check-In 2 Due by end of class in Teams |

<!-- <img src="https://pbs.twimg.com/media/EatR2YNU4AIzJ8N.jpg" alt="filter pset blur" height="400"> -->

### Function Practice Problem

- We are taking the concepts from `max.c` and instead of getting the max value from the array, you are to average the numbers and return that value to a print statement within `main`
- Below is the starter code. I have only included getting the number of elements and assigning values to the array. Your job is to write the function, and to place the function call within a print statement. Make sure to include the function declaration where appropriate.
- In comments in your code, identify the function declaration, function definition, and function call
- When you have compiled, run and fixed any bugs in your code, take a screenshot of the completed program and upload that in the Canvas assignment.
- Starter code:
  ```c
    #include <stdio.h>

    int main(void)
    {
        int n;
        do
        {
            n = get_int("Number of elements: ");
        }
        while (n < 1);

        int arr[n];

        for (int i = 0; i < n; i++)
        {
            arr[i] = get_int("Element %i: ", i);
        }

  
    }
  ```

<meta http-equiv="refresh" content="300"/>