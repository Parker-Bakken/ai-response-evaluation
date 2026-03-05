# Example 07 — Python reverse list

## Prompt
How do I reverse a list in Python?

## Candidate Response A
You can reverse a list using slicing:

```python
my_list = [1,2,3,4]
reversed_list = my_list[::-1]
print(reversed_list)
my_list.reverse()
