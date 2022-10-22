This is a template for the EDAV final project. It is based on the template created with *File, New Project..., New Directory, Book Project using bookdown* in RStudio. 


## ABSOLUTE ESSENTIALS

*If you have any difficulties or have feedback of any kind, please file an issue or communicate through [Discussions](https://github.com/jtr13/EDAVtemplate/discussions).*

### Copy this template

- [ ] 1. Click the green "Use this template" button above.  DO NOT FORK THE REPO. Choose a descriptive name for your repo, such as "federalbudget" or "AIDSdeaths".  (If you change your mind before you do any work, delete your new repo and start over.)

- [ ] 2. In the Description field, write: "Bookdown source files for EDAV final project".

### Set up GitHub Pages	
- [ ] 1. On the home page of your repo, click Settings. Click the "Pages" section on the left. Change **Source** from **None** to **main**, change **/ (root)** to **/docs** folder, and click Save. Above the **Source** line, a bar will appear with your book's URL. The bar will initially be blue and indicate that your book is *ready* to be published and will change to green once it is published. Copy the URL. (Note that sometimes there is a delay until your book actually appears at that URL. If it doesn't appear after a few minutes, make a change and commit it to trigger a GitHub Pages build.)	

- [ ] 2. Click the gear button near "About" on the home page of the repo and paste your book URL into the **Website** field that appears on the right.

### Clone the repo

- [ ] 1. Clone your new repo with *File, New Project..., Version Control, Git* in RStudio.

### Edit some key files

- [ ] 1. In `index.Rmd`, change YOUR TITLE HERE to your title.

- [ ] 2. In `index.Rmd`, change YOUR NAMES HERE to your names.

- [ ] 3. In `_bookdown.yml`, change YOUR GITHUB USERNAME to your GitHub username in the two places it appears.

- [ ] 4. In `_bookdown.yml`, change YOUR GITHUB REPO to your GitHub repo name in the two places it appears.

(Note that 3. and 4. provide links to the `.Rmd` files of your project for editing and viewing. If you move your `.Rmd` files you will need to update these file paths. Once your book is rendered, test that the edit (pen) and view (eye) buttons work.)

- [ ] 5. In `_output.yml`, change YOUR SHORT TITLE to a shortened version of your title. (Leave the "after:" line indicating that the book was published with bookdown as is.)

### Render the book

- [ ] 1. Install **bookdown** with `install.packages("bookdown")`. If you already have it, update to the most recent version.

- [ ] 2. Render locally with `bookdown::render_book("index.Rmd")` or clicking the *Build book* button which should appear in the Build tab (in the same pane as Environment, History, Connections, ...).

- [ ] 3. Use `browseURL("docs/index.html")` to view your book locally (or just open `index.html` in a browser).

- [ ] 4. If it looks good, commit and push all changed files to GitHub. 

(You will need to repeat steps 2 and 4 every time you wish to update the book online.)

### Edit README	

Once you've completed these steps, delete the content of this **README** and add a short description of your project with a link to the book URL. It would be appreciated if you add the following to the end:	

*This repo was initially generated from a bookdown template available here: https://github.com/jtr13/EDAVtemplate.*	

### Demo Video	

A demo video showing how to create a **bookdown book** following these similar instructions: http://bit.ly/fiveminutebookdown Note that this video uses a different template.

### Additional features	

Please consult the official guide to **bookdown**: https://bookdown.org/yihui/bookdown



