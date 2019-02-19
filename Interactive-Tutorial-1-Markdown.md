# Interactive Tutorial 1: Markdown

## Working with Markdown

Press `Ctrl + Shift + M` to open a formatted preview on the right.
Done!

## Basic Text

Write two sentences about yourself, each in a different paragraph.

<!--- Write your answer here. --->
My name is Lily and I am a senior.

I study Environmental Engineering!

## Headers

Make a 3rd level header with your name:

### Lily Falk

## Emphasis

Write 4 of your favorite words using each type of emphasis:

*preposterous* **winter** ***squiggle*** ~~toothbrush~~

## Lists

Make an ordered list of 3 things you hope to achieve this semester, and elaborate on them with sub items. Then, make an unordered list of 3 classes that you're taking this semester:

1. Learn in my classes
    1. stay on top of coursework and enjoy material
2. Have fun
    1. Spend time with friends, exercise, do activities
3. Make progress on StaRS FiNE
    1. fabricate, test, trouble shoot

- safe water on tap (CEE 4530)
- Linear Algebra
- Engineering Computation

## Links

Write a sentence describing your major, and insert a link to your major's department website:

My major is [Environmental Engineering](https://bee.cals.cornell.edu/undergraduate/environmental-engineering-program/) where we work to engineer the environment.

## Images

Insert the Cornell seal image with:
  1. A relative file path(`/images/Cornell_University_seal.png`)
  2. A URL (https://raw.githubusercontent.com/AguaClara/aguaclara_tutorial/master/Images/Cornell_University_seal.svg.png)

![Cornell Seal](`/images/Cornell_University_seal.png`)
![Cornell Seal](https://raw.githubusercontent.com/AguaClara/aguaclara_tutorial/master/Images/Cornell_University_seal.svg.png)

<p align="center"> <img
src="https://raw.githubusercontent.com/lilyfalk/aguaclara_tutorial/master/fine_cornell_logo_black.pngf" width= "350"> </p>

## Code Formatting

Put the name of this file in an in-line (single backtick) code format.

`Interactive-Tutorial-1-Markdown.md`

Put the following text in a Python-formatted code block:

```
def foo():
    print("Particles of a feather...")
    print("...floc together!")
```

```python
def foo():
    print("Particles of a feather...")
    print("...floc together!")

```

## Tables

Create a table listing your 3 favorite animals, books, and places on campus. Use a different alignment for each column.

| Animals| Books | Places on Campus |
| --- | :---: | ---: |
| Lion | Extremely Loud and Incredibly Close | Klarman |
| Dolphin | Time and Again | Triphammer |
| Monkey | My bio textbook | running trails |

## Blockquotes

Write your favorite quote. It must be attributed to Albert Einstein.

> "Engineers should be promiscuous" - Albert Einstein

## Horizontal Rules

Add a horizontal rule:

---

## LaTeX Formatting

Copy the equation towards the end of the [Markdown tutorial](https://github.com/AguaClara/aguaclara_tutorial/wiki/Markdown#latex-formatting) and paste it here:

$$ a^2 + b^2 = c^2 $$
