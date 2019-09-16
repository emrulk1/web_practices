### Instructions

- Kindly do only what is asked in the tasks. Do not do anything extra. Consider that what is not said is not required.
- Until instructed, do all tasks in a single HTML file. This file will be called as the index file in future, but it is not mandatory to name it `index.html`.
- Kindly do not create any file or directory unless specified in the question. If you do, this may confuse you when a future question tell you to create directories and refer to files from within them.
- You can use images hosted online. No need to download images offline to use.
- If dimensions of a table or a list is not defined, assume the least possible value. (For example, 1x1 size for a table, and 1 item for a list.)
- Use only HTML and CSS to complete the tasks until explicitly asked otherwise.
- In case of content for HTML tags, use generic words, with numbers if necessary. (For example, just "paragraph" for a paragraph; "item1" and "item2" for a list with 2 items; "r1c1", "r1c2", "r2c1", etc. in case of table cells.)
- Unless specified, follow natural order in adding your code to the document. Add your code of each task after the code of the previous task. (Which means that the image from task 3 will appear after the table from task 2; and following the image will be the code from task 6, since task 4 and task 5 have specific instructions.)
- Do not assume an "input field" means the HTML `<input>` tag. The result should look like an input field to the eye. Whatever HTML tag you use to make it so is not the concern, as long it does what is asked in the question.
- From task 22 onward, write all CSS rules you need in the external CSS file unless explicitly told to do otherwise. Name that file whatever you like, but this file will be called the main CSS file to refer in the future.
- From task 22 onward, in the CSS-focused questions, when you are asked to use CSS to do something, do not remove or modify either any of your existing CSS or the content of the CSS file given in the question. Just add more valid CSS rules to override them in the browser rendering.
- From task 22 onward, in order to apply your own CSS, add whatever `class` attributes you think necessary to whatever HTML tags. But do not add any `id` attribute unless explicitly asked to do so. And, try to keep the class names generic, so they do not coincide with class names provided in any question (if any).
- From task 22 onward, when you are asked to apply CSS, create additional HTML elements if necessary (e.g., a container `<div>` for an `<img>`). But do try to keep the amount of such additional tag creation to a minimum.

All "estimated time needed" values have been calculated with some margin for searching what you will be looking for to complete the tasks, and for reading up on some related things you found. So, in almost all the cases – unless you are very unlucky, or inefficient in the way you search – you will need less time than what is given. And, if you at least know the names of the tags and properties you need to use, you will need about 1/5th to 1/6th of the time.

By the way, keep in mind that the time does not necessarily indicate difficulty or the amount of code you need to write. Since some time to read up on related topic is included, it can vary greatly for solutions that apply different methods for the same problem.

You do not need to look at the hints just because they are there. Ignore them if you want some challenge. But feel free to make use of them if in a hurry.

_**Note:** Please use Git, and commit at least after every task is completed. If you think more commits are necessary or better in any task, please do so. (Especially when the same task has a subtask that reverts the affect of the previous subtask (e.g., making it invisible, and then making it visible again) – so, putting both the code for subtasks in the same commit will effectively just show the result of the later subtask.)_

### Task 1

Create a simple web page, without any visible content.

_Estimated time needed for completion: 10m_

### Task 2

Create:

- an unordered list with 2 items (put "item1", "item2" as content), 
- a table with 2 rows and 2 columns (put "c1r1", "c2r1", etc. as content).

_Est. time: 10m_

### Task 3

- Add a random image which will be 50% width of the screen.
- Center the image horizontally.

_Est. time: 15m_

### Task 4

- Inside the 2nd item of the already-created list, create a list with 3 items.
- Create a table inside the 2nd item of the nested list.
- In the newly-created table, add a random image of fixed size: `200px` height and `300px` width.

_Est. time: 15m_

### Task 5

- Add an HTML `id` attribute of value `nestedList` to the nested list created in the last task.
- In the 3rd item of `nestedList`, add a hyperlink, which –
  - should show the content "HTML tag list".
  - should show the full form of the abbreviation "HTML" when the word "HTML" is hovered. (This should be done without using any CSS.)
  - should redirect to this link: `https://html.com/tags`.

_Est. time: 20m_

### Task 6

Show the HTML code necessary to create a text-justified paragraph with an image inside, in such a way that all indentations are preserved. Like the `dt` and `dd` tags are indented here:
```HTML
<dl>
    <dt>item</dt>
    <dd>description</dd>
</dl>
```

Kindly note that _you_ are asked to write code for _a paragraph with an image inside_.

Just put the word "paragraph" as the content of the paragraph. It is not mandatory to actually put the link of an image to the tag – you can just leave an empty tag for the image.

Use whichever HTML tag is necessary to show the indentation. Do not use CSS this.

_Est. time: 25m_

### Task 7

Create a box (use any tag you like, but with a visible border – of whatever style you like) and in it:
- Create an input field that will only take integer numbers between and including 51–87.
- Create an input field in which you can safely type a password without anyone noticing over your shoulder.
   > (Hint: There is an attribute for this.)
- Create a question (content: "question1") with 2 options ("option1", "option2") that can not be selected at the same time. (Meaning, if you select "option1" first and then select "option2" again, "option1" will be deselected automatically.)
- Create a question with 2 options that _can_ be selected at the same time.
- Create an input field that only takes email addresses as valid input.

_Est. time: 35m_

### Task 8

- Wrap all the elements created in the last task in an HTML `<form>` tag, and add a button which will reset all the input fields (clear all content) when clicked.
- Add an HTML `id` attribute of value `form` to the form.

_Est. time: 15m_

### Task 9

Inside the form created in the last task –

- Add an input field for entering text that can be stretched by the user (i.e., user can click on the corner and drag to make the field bigger).
- Add a select option for gender. Provide two boxes/circles/buttons for the user two select, but they should be preceded by the texts "male" and "female". And when the user clicks on a text – not on the box/circle/button itself – the option should get selected. The user should not be able to select both options simultaneously.
   (Clarification: Make it so that an input option gets selected even if the user clicks on its text only. And do this _without using JabaScript_.)

_Est. time: 25m_

### Task 10

- In the list with the `id` value `nestedList`, change the default list style (filled circles, most likely) to numbers, without changing the HTML tags.
- Add an `id` attribute of value `outerList` to the other/outer list. Change its default list style to "a", "b", "c", ... etc, without changing the HTML tags.

> (Hint: Read up on CSS pseudo-classes and pseudo-elements.)

_Est. time: 25m_

### Task 11

- Before the list of `id` value `outerList`, add a heading of `<h3>` with this content: "This is the outer list". Make the word "outer" bold without using any CSS.
- Add a "1" at the end of the heading in superscript (like a reference). Add an `id` of value `ref` to it.
- At the end of your HTML file, write "There are 2 lists" in a paragraph, in a font smaller than the default size. Make the font size smaller without using any CSS. Add an `id` of value `footnote` to it.
- Put a line _over_ this footnote without adding a new HTML element or using any `border`-related CSS property.

_Est. time: 20m_

### Task 12

- Create a progress bar to show how many tasks so far you have completed (among 1-11) without using any CSS.
- Create another progress bar to show the same. This time, you can use CSS, but you can not add any more HTML element. Do it using only one tag.

_Est. time: 25m_

### Task 13

Do the following without using any CSS (_or JS_):

- Modify the table inside the list of `id` value `nestedList` in such a way that it will show the content "table inside nested list" in a small pop-up over it when hovered.
- Add another cell in the same row of the table with the content "r1c2". Make it so that, when hovered, the cell will show the content "row 1 column 2".
- Modify the first progress bar created in task 12 in such a way that, when hovered, it will show the following two sentences separated by a blank line. Like this:
```
This progress bar is made without CSS.

But the next one is not.
```

_Est. time: 15m_

### Task 14

Create a table that looks like this:
```
---------------------------------
|     heading1    |             |
-------------------   heading2  |
|  sub1  |  sub2  |             |
---------------------------------
|  3.1   |  3.2   |  3.4 / 3.5  |
---------------------------------
|  4.1   |  4.2   |  4.4 / 4.5  |
---------------------------------
|  5.1   |  5.2   |  5.4 / 5.5  |
---------------------------------
```

_Est. time: 20m_

### Task 15

Try to show `https://www.wikipedia.org` in a small box/opening/window on your page. No CSS is necessary.

> (Hint: There is an HTML tag for showing other websites.)

_Est. time: 15m_

### Task 16

Create a box (with visible border to identify easily) with the content "a magic box", but make it so that you can directly type in it, without using any JS.

_Est. time: 10m_

### Task 17

Create a box (with visible border) and in it:
- Add a dropdown with the options "option1" to "option5". "option3" should be selected by default.
- Below it, add 3 buttons.
  - The middle button one should _not_ be clickable.
  - Make the 3rd button hidden without using any CSS or JS. (It will be in the code but will not appear on the webpage in the browser.)
- Create an input field where the user can not type more than 16 characters one after another. The field should show "16 characters only" as a placeholder by default.

_Est. time: 15m_

### Task 18

Create another input field inside the box created in the previous task. The input field should have the words "already filled" _pre-written_ in it.

The specialty of a placeholder is it can not be selected and it goes away once you click on the input field to type. The purpose of this task is not to create that. Instead, you need to make the field appear as though you have already typed the words "already filled" in it.

_Est. time: 10m_

### Task 19

Create an input field where, while typing, you will get suggestions from a set of predefined values/options. Do this with HTML only.

_Est. time: 20m_
