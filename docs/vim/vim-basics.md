# Vim Basics

## Basic Movements

### Side Movements

- h - move left
- j - move down
- k - move up
- l - move right

### Moving By Words

- Moving the cursor by charter can take long time i.e. using h and l to move cursor in a current line.
- There are better methods for moving the cursor in a current line.
- But right now we could use **w** to move cursor by word forward.
- In same way we could use **b** to move cursor by word backword.

---

## Writing The Text

- In _other text_ editors for writing text we directly start typing.
- In vim we can't type directly because in vim we will be in normal mode by default.
- To start typing inside vim we should go inside insert mode.
- There are many methods for doing it but the simple method is by pressing **i**.
- Now we can start typing like in normal editors.
- After we completed typing we should back to normal by pressing **<esc>** key.

---

## Visual mode

### Small v

- In vim we could highlight the text by using visual mode.
- To go into visual mode use **v** keybinding.
- After entering visual mode we could highlight more text by moving cursor i.e. use normal mode movements i.e., h,j,k,l and so on.

### Capital V

- Highlighting text by using above method is good but if we want highlight many lines then using capital **V** would be great option.
- we could leave visual mode and go to normal mode just pressing **<esc>** key.

---

## Copy And Paste

### Copying

- Use visual mode to highlight the text that we want to copy.
- After that press **y** letter to copy the vim register and we automatically go to normal mode.
- In vim copy is called yank.

### Pasting

- Go to the place where you want to paste the text and press **p** it will paste the text from the vim register.
- By default you can't paste the text from outside of vim to inside of vim vice versa.

---

## Delete The Text

- In the same way as yanking we could select or highlight the text that we want remove.
- After that to delete the text by pressing **d**

---

## Saving And Exiting The File

### Saving The File

- To save the file we should make sure that we are in normal mode.
- Press **:w** where colon means that we are entering command mode and w means we are writing to the file.

### Exiting the Vim

- To exit the vim press **:q** where q means quit.
