## Python: Write Instructions for Building an f-String

- Write step-by-step instructions for building a Python f-string
- TIP: Start each step with a verb (an action word)
- Write instructions that are brief and specific
- Use the words from the Word Bank in your explanations
- Include sample code for each step
- Try to write your instructions in 5 - 7 steps
- Delete the markdown for any steps you don't use
- Copy and paste the web address (URL) of your copy of this repository to Google Classroom when you are finished with this activity

## Word Bank
> `print( )` function, variable, assignment operator, value, lowercase f, single quotation marks, double quotation marks, curly braces, placeholder

---
### How to Build an f-String in Python 

1. Decide what you want to write, in this case I want to display the function len() in a sentence.
```python
len('something')
```
2. Define your function and (optional) assign it to a variable.
```python
variable = len('something')
```
3. Create a print function that includes your sentence.
```python
variable = len('something')

print('the word something has __ characters')
```
4. Inside the brackets of the print function, but before the string put an f (this allows you to make it an f-string)
```python
variable = len('something')

print(f'the word something has __ characters')
```
5. Inside the string, at the desired spot put your variable incased in curly brackets.
```python
variable = len('something')

print(f'the word something has {variable} characters')
```
6. Test it out! I can't see the exact problem you're having but most, if not all of the problems you could have can be solved by just double checking.
```python
variable = len('something')

print(f'the word something has {variable} characters')

# the output should say "the word something has 9 characters" in this example
```
