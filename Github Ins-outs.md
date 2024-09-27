## To manually upload a file to a new GitHub repository, follow these steps:
1. Create a New Repository

    Go to GitHub and sign in to your account.
    Click on the + icon in the top-right corner and select New repository.
    Fill in the necessary details such as:
        Repository name (e.g., "my-repo").
        Description (optional).
        Choose between Public or Private repository.
    Click Create repository.

2. Upload Files

    Once your repository is created, you'll see a page with options to initialize your repository.

    Click the "upload an existing file" link (below the "Quick setup" section) or click "Add file" > "Upload files" (top-right corner).

    On the next screen, drag and drop your file(s) into the box, or click "choose your files" to browse your computer and select the file(s).

    Optionally, add a commit message describing the upload.

    Click "Commit changes" to upload the file(s) to the repository.

Your file(s) should now be uploaded and visible in the repository!
---

## Github Markdown Formatting 
Title: Use # for the main title. You can use up to six # symbols for subheadings.

Bullet Points:
Unordered List: Use -, *, or + for bullet points.
Ordered List: Use numbers followed by a period.

SQL Script Window:
Code Blocks: Use triple backticks (```) along with a language identifier (like sql, python, etc.) to format code blocks. For example:

```sql
select* from Table_Name;
```

```python
print("Hello World")
```
To close the code block, place another set of triple backticks (```) on a new line immediately below the last line of code.

You can find the backtick key (`` ` ``) on most keyboards, usually located just below the `Esc` key.

---


Images: Use the ![]() syntax to add images.

Links: Use [Link text](URL) to add hyperlinks.

Inline Code: Use single backticks (`) for inline code.

Bold: Use double asterisks or underscores (**bold** or __bold__).

Italic: Use single asterisks or underscores (*italic* or _italic_).

Horizontal Rule: Use three dashes, asterisks, or underscores.

---
## How to Open Jupyter Notebook

1. Open **Anaconda Prompt**.
2. Navigate to the storage partition (e.g., `H:`):
   
   ```bash
   H:
   cd 1.1
   cd 1.1
   jupyter notebook
   ```

open anconda prompt 
h:               (Storage partition location
cd 1.1 (tab)     (Folder location, first letter or number then press tab key to auto select the folder, 1.1 is my folder name's first three charectars)
cd 1.1 (tab)
Jupyter notebook


Jupyter Notebook User Guide
1. Getting Started

    Launching Jupyter Notebook: Open your terminal (or Anaconda Prompt) and type:

    bash

    jupyter notebook

    This will open the Jupyter dashboard in your default web browser.

2. Creating a New Notebook

    In the Jupyter dashboard, click on the New button and select Python 3 (or any other kernel you want to use).

3. Notebook Interface

    Cells: Notebooks consist of cells, which can be of different types:
        Code Cells: For executing code.
        Markdown Cells: For documentation and notes (use Markdown syntax).

4. Running Cells

    To run a cell, click on it and press Shift + Enter. This executes the code and moves to the next cell.

5. Editing Cells

    Code Cells: Click in the cell to edit. Use Enter to start editing and Esc to enter command mode.
    Markdown Cells: To format text, write in Markdown syntax. To render the Markdown, run the cell using Shift + Enter.

6. Cell Operations

    Add Cell:
        In command mode, press A to add a cell above or B to add a cell below.
    Delete Cell:
        Select the cell, enter command mode (Esc), and press D, D.
    Move Cells:
        Use Up and Down arrow keys to navigate and X to cut or C to copy. Use V to paste.

7. Saving and Exporting

    Save Notebook: Click the save icon or press Ctrl + S.
    Exporting: Go to File > Download as to export in different formats (e.g., HTML, PDF, etc.).

8. Using Extensions

    You can enhance functionality with Jupyter Notebook extensions. Consider installing nbextensions for added features like code folding and table of contents.

9. Keyboard Shortcuts

    Familiarize yourself with useful shortcuts:
        Command Mode (blue border): A (add cell above), B (add cell below), D, D (delete cell).
        Edit Mode (green border): Ctrl + Enter (run cell), Shift + Enter (run and select next).

10. Best Practices

    Use Markdown cells for notes and explanations to make your notebook more readable.
    Keep your code organized and modular; use functions when possible.
    Regularly save your work!



---



