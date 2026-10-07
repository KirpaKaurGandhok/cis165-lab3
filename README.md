# Fundamentals_of_Programming - Lab 3: C++ Output and Time Calculations — Build, Test, and Explain with AI

# Course Section
## CIS-165-B030

## My Plans for Both Programs
### diamond.cpp
I plan to use cout statements to print each line of the diamond. Then, I will use the right number of spaces and asterisks to match the required pattern.

### game_time.cpp
I plan to create 2 integer variables to store the times for Level 1 and Level 2 as 78 and 144 minutes. Then, I would utilize integer division and the remainder operator to calculate the hours as well as the remaining minutes. Finally, I'll calculate the difference in time between the two levels and then display all three results.

## Testing the Programs
| Program & test | Values or pattern checked | Expected results | Actual results | Match or correction |
|---|---|---|---|---|
| Diamond | Seven required lines | Correct spaces and asterisks | Correct spaces and asterisks | Match |
| Game Time — assigned values | 78 and 144 minutes | Level 1 = 1 hour, 18 minutes; Level 2 = 2 hours, 24 minutes; Difference = 1 hour, 6 minutes | Level 1 = 1 hour, 18 minutes; Level 2 = 2 hours, 24 minutes; Difference = 1 hour, 6 minutes | Match |
| Game Time — changed values | 95 and 185 minutes | Level 1 = 1 hour, 35 minutes; Level 2 = 3 hours, 5 minutes; Difference = 1 hour, 30 minutes | Level 1 = 1 hour, 35 minutes; Level 2 = 3 hours, 5 minutes; Difference = 1 hour, 30 minutes | Match |

## Explaining my code
### How do your output statements create the required shape? How did you check spaces that are difficult to see?
Each cout statement prints out one line of the diamond. I checked the spaces by comparing my output to the required pattern shown in the instructions & making sure that the spaces and asterisks matched completely.

### How do integer division and the remainder operator convert total minutes into hours and remaining minutes?
Dividing the total minutes by 60 gave the number of complete hours. The remainder operator gave the minutes left over. For instance, 78 / 60 equals 1 hour and 78 % 60 equals 18 minutes.

### Trace the assigned Level 1 and Level 2 values through your variables, including the calculation of the difference.
Level 1 is 78 minutes, so 78 / 60 equals 1 hour and 78 % 60 gives 18 minutes remaining. Similarly, Level 2 is 144 minutes, so 144 / 60 gives 2 equals and 144 % 60 gives 24 minutes remaining.
The difference is 144 - 78 = 66 minutes. Then 66 / 60 gives 1 hour and 66 % 60 gives 6 minutes. Thus, Level 2 took 1 hour and 6 minutes longer.

### Why does the assignment ask you to store calculations in variables before using cout?
Storing calculations in variables makes the code easier to both read and understand. It also makes the calculations much easier to check & fix in case of any errors.

## Compiling & Running Both Programs
### diamond.cpp

#### to compile
g++ -std=c++17 -Wall -Wextra diamond.cpp -o diamond

#### to run
./diamond

### game_time.cpp

#### to compile
g++ -std=c++17 -Wall -Wextra game_time.cpp -o game_time

#### to run
./game_time
