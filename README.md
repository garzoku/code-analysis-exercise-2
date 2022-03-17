# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (floor){
  if (floor <= 0){
    return floor
  }

  let offset = 1
  if (floor >= 13){
    offset = 2
  }

  return floor - offset
}
```

| Input | Output |
| ----- | ------ |
|  10   |    9   | 
|  0    |    0   | 
|  15   |    13  | 
|  3    |    2   |
|  2    |    1   |
|  13   |    11  |
|   0   |    0   |
|   1   |    0   |
|   2   |    1   |
|   3   |    2   |
|   4   |    3   |
|   5   |    4   |
|  10   |    9   |
|  11   |   10   |
|   12  |   11   |
|   13  |   11   |
|   14  |   12   |

<table>
  <tr>
    <th>What does this program do?</th>
    <td>1). The function accepts a floor as a number.<br>
2). If floor is less than or equal to 0, the floor number is returned.<br>
3). If floor is not less than or equal to 0, the first if statement is skipped.<br>
4). The variable named offset is assigned a value of 1.<br>
5). If floor is more than or equal to 13, the value for offset is changed to 2.<br>
6). The function then returns the result of floor minus offset.<br>
7). This program appears to be like a mathematical floor function. It returns the largest number that is less than or equal to either 0 or 13.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
