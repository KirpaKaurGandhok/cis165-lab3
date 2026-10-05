# Fundamentals_of_Programming - Lab 3: C++ Output and Time Calculations — Build, Test, and Explain with AI

## Plans for Diamond and Video Game Level Time Programs
### diamond.cpp
My plan is to use cout statements to print each line of the diamond. I will use the correct number of spaces and asterisks to match the required pattern.

### game_time.cpp
My plan is to create two int variables to store the Level 1 and Level 2 times of 78 and 144 minutes. I will use integer division and the remainder operator to calculate the hours and remaining minutes. I will also calculate the difference between the two levels and display all three results.

## Testing my Programs
| Program and test | Values or pattern checked | Expected results | Actual results | Match or correction |
|---|---|---|---|---|
| `diamond.cpp` | Seven required lines | Correct spaces and asterisks | Correct spaces and asterisks | Match |
| `game_time.cpp` — assigned values | 78 and 144 minutes | Level 1 = 1 hour, 18 minutes; Level 2 = 2 hours, 24 minutes; Difference = 1 hour, 6 minutes | Level 1 = 1 hour, 18 minutes; Level 2 = 2 hours, 24 minutes; Difference = 1 hour, 6 minutes | Match |
| `game_time.cpp` — changed values | 95 and 185 minutes | Level 1 = 1 hour, 35 minutes; Level 2 = 3 hours, 5 minutes; Difference = 1 hour, 30 minutes | Level 1 = 1 hour, 35 minutes; Level 2 = 3 hours, 5 minutes; Difference = 1 hour, 30 minutes | Match |

## Explaining my code
### How do your output statements create the required shape? How did you check spaces that are difficult to see?
Each cout statement prints one line of the diamond. I checked the spaces by comparing my output to the required pattern and making sure the spaces and asterisks matched.

### How do integer division and the remainder operator convert total minutes into hours and remaining minutes?
Dividing the total minutes by 60 gives the number of complete hours. The remainder operator gives the minutes left over. For example, 78 / 60 gives 1 hour and 78 % 60 gives 18 minutes.

### Trace the assigned Level 1 and Level 2 values through your variables, including the calculation of the difference.
Level 1 is 78 minutes, so 78 / 60 gives 1 hour and 78 % 60 gives 18 minutes. Level 2 is 144 minutes, so 144 / 60 gives 2 hours and 144 % 60 gives 24 minutes.

The difference is 144 - 78 = 66 minutes. Then 66 / 60 gives 1 hour and 66 % 60 gives 6 minutes. Therefore, Level 2 took 1 hour and 6 minutes longer.

### Why does the assignment ask you to store calculations in variables before using cout?
Storing calculations in variables makes the code easier to read and understand. It also makes the calculations easier to check and fix if there is an error.

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
