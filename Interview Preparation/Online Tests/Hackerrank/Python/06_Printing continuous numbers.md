- Question
	- The included code stub will read an integer, , from STDIN.
	- Without using any string methods, try to print the following: ![[Pasted image 20231031202839.png]]
		- Note that "" represents the consecutive values in between.
	- **Example**  
		- Print the string .
	- **Input Format**
		- The first line contains an integer .
	- **Constraints**
		- ![[Pasted image 20231031202903.png]]
	- **Output Format**
		- Print the list of integers from  through  as a string, without spaces.
	- **Sample Input 0**
		- 3
	- **Sample Output 0**
		- 123

```python
if __name__ == '__main__':
    n = int(input())
    result = ''
    for i in range(1, n+1):
        result += str(i)
        
    print(result)
```