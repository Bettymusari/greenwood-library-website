# greenwood-library-website
Capstone Project : Enhancing a community library website
Set up: I created a repository on Github, initialised it with a README.md file and then cloned it to my local machine.
The repository cloned to my local machine is now my main branch.
In my VSCode Editor, I created the following files for each of the web pages:
1. home.htlm
2. about_us.html
3. events.html
4. contact_us.html
Then I added contents into each of the files.
To stage each of the files, i ran the command "git add <file name>"
To commit of these changes on each of the files, I ran the command "git commit -m <file name>
Then I pushed the changes directly to the main branch to simulate the team's existingcodebase for the website using "git push origin main"
Now to simulate Morgan and Jamie's work, first Morgan

Morgan's work
I created a branch for Morgan by switching to a new branch named "add-book-reviews"using the command, :git checkout "add-book-reviews"
Using the "touch" command, I created a new file named "book_reviews" to represent the Book Review Section.
I added text contents into the file.
Then I staged, commit and pushed the changes with a message: "add book reviews section
I also pushed the 'add-book-reviews" branch to Github using the command: git push origin add-book-reviews. 
On Github, I raised a Pull Request (PR) by clicking on the "create pull request" button
Since there was no conflict,  I made a comment that "we are good to go", then i merged his work with the main and deleted his branch.

Jamie's work
Switched to Jamie's branch with "git checkout update-events"
I then pulled the latest changes from the main branch "git pull origin main"
Added changes to the events.html file in Jamie's branch
I staged, commit and then pushed again to the main.
Another PR was raised for Jamie's work, reviewed, and then passed for merging.
Jamie's branch was also successfully merged into the main branch and then his branch was deleted.
