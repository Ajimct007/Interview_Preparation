- Question
	- Task
		- The provided code stub reads two integers from STDIN,  and . Add code to print three lines where:
			- The first line contains the sum of the two numbers.
			- The second line contains the difference of the two numbers (first - second).
			- The third line contains the product of the two numbers.
		- Example
			- Print the following:
				- 8
				- -2
				- 15
	- Input Format
		- The first line contains the first integer, .
		- The second line contains the second integer, .
	- Constraints
		- ![[Pasted image 20231031185718.png]]
	- Output Format
		- Print the three lines as explained above.
	- Sample Input 0
		- 3
		- 2
	- Sample Output 0
		- 5
		- 1
		- 6
	- Explanation 0
		- ![[Pasted image 20231031185817.png]]

## Python code

```python
if __name__ == '__main__':
    a = int(input())
    b = int(input())
    print(a + b)
    print(a - b)
    print(a * b)
```
