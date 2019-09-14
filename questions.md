### Instruction

- Kindly do only what is asked in the tasks. Do not do anything extra. Consider that what is not said is not required.
- Until instructed, do all tasks in a single HTML file. This file will be called as the index file in future, but it is not mandatory to name it `index.html`.
- You can use images hosted online. No need to download images offline to use.
- If dimensions of a table or a list is not defined, assume the least possible value. (For example, 1x1 size for a table, and 1 item for a list.)
- Use only HTML and CSS to complete the tasks until explicitly asked otherwise.
- In case of content for HTML tags, use generic words, with numbers if necessary. (For example, just "paragraph" for a paragraph; "item1" and "item2" for a list with 2 items; "r1c1", "r1c2", "r2c1", etc. in case of table cells.)

_**Note:** Please use Git, and commit at least after every task is completed. If you think more commits are necessary or better in any task, please do so._

### Task 1

Create a simple web page, without any visible content.

### Task 2

Create:

- an unordered list with 2 items (put "item1", "item2" as content), 
- a table with 2 rows and 2 columns (put "c1r1", "c2r1", etc. as content).

### Task 3

- Add a random image which will be 100% width of the screen.
- Center the image horizontally.

### Task 4

- Inside the 2nd item of the already-created list, create a list with 3 items.
- Create a table inside the 2nd item of the nested list.
- In the newly-created table, add a random image of fixed size: `200px` height and `300px` width.

### Task 5

- Add an HTML `id` attribute of value `nestedList` to the nested list created in the last task.
- In the 3rd item of `nestedList`, add a hyperlink, which –
  - should show the content "HTML tag list".
  - should show the full form of the abbreviation "HTML" when the word "HTML" is hovered.
  - should redirect to this link: `https://html.com/tags`.

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

Use whichever HTML tag is necessary to show the indentation.

### Task 7

Create a box (use any tag you like, but with a visible border – of whatever style you like) and in it:
- Create an input field that will only take integer numbers between and including 51–87.
- Create an input field in which you can safely type a password without anyone noticing over your shoulder. (Hint: there is an attribute for this.)
- Create a question (content: "question1") with 2 options ("option1", "option2") that can not be selected at the same time.
   (Meaning, if you select "option1" first and then select "option2" again, "option1" will be deselected automatically.)
- Create a question with 2 options that _can_ be selected at the same time.
- Create an input field that only takes email addresses as valid input.
