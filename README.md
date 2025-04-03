# Alphabet_python 🧂
Tired of your professor asking you to display <strong>letters</strong> or <strong>words</strong> in Python? 😫
Just use this, and boom! 💥💥💥<br>
You can easily generate <strong>letters</strong> in your project! 🤩

## How does it work? 🤓
Place the file in \EduPython\App\Lib if you're using EduPython, or simply in the same folder as your project. 📁

Import it using:

```python
from alphabet import *
```
💢 This line is required for the script to work!

## Getting Started 🐤
The program first asks you to define:

- <strong>Width</strong> – The width of your letters

- <strong>Length</strong> – The height of your letters

- <strong>Y</strong> – The vertical margin position 

- <strong>X</strong> – The horizontal margin position

- <strong>Color</strong> - The color of your letters (visit https://cs111.wellesley.edu/reference/colors to see them)

## Writing Letters 💻
To display a <strong>letter</strong>, type the <strong>letter</strong> followed by ().
For example, to display "X":

```python
X()
```
To add space between <strong>words</strong>, use ``space()``.
To move to the next <strong>line</strong>, use ``enter()``.

## Example: 👐
Here’s how you can write the <strong>sentence</strong> "A WORD FROM ME" using Alphabet.py:

```python
from alphabet import *

A()
enter()
W()
O()
R()
D()
space()
space()
space()
F()
R()
O()
M()
enter()
M()
E()
```
## Planned Updates 😴
✔ Improve my English 😅<br>
✔ Add special characters like ;,.:/ etc.<br>
✔ Support for numbers! 🎉<br>

## Found a bug?
Let me know! There are bound to be a *few*. 😆


### List of all functions :
```python
A() #Display letter A. Note that you can change A to any other letters
space() #Make a space that is 1/4 of length
enter() #Make you move to the next line
initialize() #Not working as expected, but you can copy/paste the block of code to see how I initialize all the letters in my module
half_circle() #Make an half_circle to the right. Note that it isn't usefull
point() #Make the .
comma() #Make the ,
semicolon() #Make the ;
hyphen() #Make the -
bracket1() #Make the (
bracket2() #Make the )
apostrophe() #Make the '
sharp() #Make the #
quotes() #Make the "
exclamation() #Make the !
interrogation() #Make the ?
```
