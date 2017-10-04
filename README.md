# Lectures for ST445, MT 2017

## Course handout page: http://lse-st445.github.io

---

## How to print slides to pdf

```bash
jupyter-nbconvert --to slides --SlidesExporter.reveal_url_prefix='https://cdnjs.cloudflare.com/ajax/libs/reveal.js/3.5.0/' ST445_wk1_admin.ipynb
```
Then:
* rename the output file to change the space before `slides` to an underscore
* browse the file in Chrome using (e.g.)
    ```
    file:///Users/kbenoit/Dropbox/GitHub/lse-st445/lectures/week01/ST445_wk1_admin.slides.html?pdf-preview#/
    ```
* Print to Preview (Mac) or just print to pdf in Landscape A4 mode, without headers and footers

See also https://github.com/lse-st445/lectures/issues/1

> Don't quote me on that please.

---

## How to update the assignment starting codes / instructions

1. Clone your own assignment repository into your own computer if you haven't:
    ```
    git clone https://github.com/[your_user_name]/[your_assignment_repository]/
    ```
2. Change your current directory to the cloned repository if you haven't:
    ```
    cd [your_assignment_repository]
    ```
3. Fetch and merge changes from the latest version of the assignment instruction on the remote server to your working directory: 
    ```
    git pull https://github.com/lse-ST445/[assignment_instruction_repository]/
    ```
4. Resolve conflicts if there are any
5. Commit the changes back to your local repository:
    ```
    git commit -a -m "[your own comment]"
    ```
6. Push the merge to your GitHub repository:
    ```
    git push
    ```
  
Reference: https://help.github.com/articles/merging-an-upstream-repository-into-your-fork/
  
