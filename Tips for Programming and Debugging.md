# Tips for Programming and Debugging

Just suggestions provided by the author, you may do more or less.

# General Steps for Programming

1. Read through the problems, know about what to do roughly.
2. Think about how to deal with it in mind, just like solving math problem. 
3. Now you may have some formulas, algorithms, or how data flows.
4. Find what kind of data structure to save input, intermediate result and final result. Or do it during writing code.
5. Write your code and run it.
6. Generally, you will find the code does not work well and need to do debugging.

#  General Steps for Debugging

1. Your code should run first, no matter its result.
2. Pass local test.
3. Pass test on Online Judge.

# Tips for Debugging

During coding, we often meet 2 problems: run time error and wrong answer.

Solve RE first, then WA. There may be a cycle, `RE->WA->RE`... Be patient with it and make efforts.

**Passing local test does not mean you can pass test on Online Judge!**

Local test is quite simple. You can construct your own test cases.

## Corner Case

Consider the initial state, the final state and whether they need special handle.

Consider the situation that your container is empty or full.

## Logic

Ensure your method can really solve the problem. Maybe think it over or write it down on paper.

Check if you use if-else statements, loops as you want and the indexes that do operations on elements.

## Print

Using ` print()` may be the most common and useful methods.

Here is a trivial example: 

```python
suki = [] 
'''
insert some elements to the list
'''
for i in range(len(suki))
	# any number you want
	if i == 0:
        print(suki[i])
        print(type(suki[i]))
```

## Comments

Sometimes, errors are caused by the previous code, but are reported later. You can use ` print()` to check the intermediate result. Or you can comment some code to check its effects.

Here is a trivial example: 

```python
# want to concatenate first name and last name
# should have even input words
suki = ['Tobiichi', 'Origami', 'Violet', 'Evergarden']
# do some operation, but wrong
# just comment it!
# suki.append('')
print(suki)
res = []
for i in range(0, len(suki), 2):
    # error happens here
    res.append(suki[i]+' '+suki[i+1])
print(res)
```

## Rubber Duck Debugging

You can explain your method and code briefly to a rubber duck, or an anime figure. You may find the problems during the process. But do not explain it to any human beings before deadline, it violates the academic integrity.

# ????????????

- Waiting ???????????????????????????????????????????????????
- Fetched ?????????????????????????????????????????????????????????????????????
- Compiling ????????????????????????
- Judging ???????????????????????????????????????
- Accepted ?????????????????????????????????
- Wrong Answer ????????????????????????????????????????????????????????????????????????????????????????????????
- Time Limit Exceeded ???????????????????????????????????????????????????
- Memory Limit Exceeded ?????????????????????????????????????????????????????????
- Runtime Error ???????????????????????????????????????????????????????????????????????????????????????????????????????????????
- Compile Error ????????????????????????
  - Chinese characters
  - single brackets

  - lack of colons
- System Error ???????????????????????????????????????????????????????????????????????????????????????
- Canceled ????????????????????????
- Unknown Error ?????????????????????
- Ignored ??????????????????

Get more information about OJ from [?????? - HydroOJ (si100.fun)](https://si100.fun/wiki/help#status).

# About

Author: magixn

Date: 2022/03/01