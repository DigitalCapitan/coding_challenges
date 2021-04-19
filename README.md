# Dart Coding Challenges

## Series of coding challenges developed/solved using the Dart language

### Structure
main.dart can be found in [bin](https://github.com/DigitalCapitan/coding_challenges/tree/main/bin)<br>
The main method is used to call all challenges and display time it takes to execute each method<br>

Source code of challenges can be found in [lib](https://github.com/DigitalCapitan/coding_challenges/tree/main/lib)<br>
List of all challenges are below<br>

Tests for all methods can be found in [test](https://github.com/DigitalCapitan/coding_challenges/tree/main/test)<br>

## Challenges
### 1. Fibonacci
The Fibonacci numbers, commonly denoted F(n) form a sequence, called the Fibonacci sequence, such that each number is the sum of the two preceding ones, starting from 0 and 1.

### 2. Robot Cleaner (Busy - Need to complete Extra Challenges)
Given a two dimensional space, in this scenario, a 2d array, create a robot R that can traverse the entire space, by moving from an index point in the 2d array to the next.
#### Rules:
- The Robot can only move horizontally or vertically (left or right, up or down)
- Traverse the entire 2d array
- The Robot can travel to spaces it has already been to

#### Example:
Start the robot at [0,0]

<table>
<tr>
<th> Start </th>
<th> Step 1 </th>
<th> Step 2 </th>
<th> Step 3 </th>
<th> Step 4 </th>
<th> Step 5 </th>
<th> Step 6 </th>
<th> Step 7 </th>
<th> Step 8 </th>
</tr>
<tr>
<td>

| |0 |1  | 2|
--- | --- | --- | ---
|0|R|.|.|
|1|.|.|.|
|2|.|.|.|

</td>
<td>

| |0 |1  | 2|
--- | --- | --- | ---
|0|#|R|.|
|1|.|.|.|
|2|.|.|.|

</td>
<td>

| |0 |1  | 2|
--- | --- | --- | ---
|0|#|#|R|
|1|.|.|.|
|2|.|.|.|

</td>
<td>

| |0 |1  | 2|
--- | --- | --- | ---
|0|#|#|#|
|1|.|.|R|
|2|.|.|.|

</td>
<td>

| |0 |1  | 2|
--- | --- | --- | ---
|0|#|#|#|
|1|.|R|#|
|2|.|.|.|

</td>
<td>

| |0 |1  | 2|
--- | --- | --- | ---
|0|#|#|#|
|1|R|#|#|
|2|.|.|.|

</td>
<td>

| |0 |1  | 2|
--- | --- | --- | ---
|0|#|#|#|
|1|#|#|#|
|2|R|.|.|

</td>
<td>

| |0 |1  | 2|
--- | --- | --- | ---
|0|#|#|#|
|1|#|#|#|
|2|#|R|.|

</td>
<td>

| |0 |1  | 2|
--- | --- | --- | ---
|0|#|#|#|
|1|#|#|#|
|2|#|#|R|

</td>
</tr>
</table>

The Robot completed this 2d array in 8 steps

#### Extra Challenge
- Add obstacles(X) to the array that the Robot cannot pass through
- Start the Robot in a random location
- Traverse the 2d array in the least amount of steps
