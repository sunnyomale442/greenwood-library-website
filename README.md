# greenwood-library-website
CAPTSTONE PROJECT

# the first task i carried out was to logon to GIT and selected the icon, new rpository at the upper right corner of the page  then named it greenwood-library-website.

# The pulic option was selected and also the README.md options was initialized then i clicked on the creat repository at the bottom of the page.
# A folder was immidiately created on my Desktop with same name and the by going on gitHUB, Cliking green icon code at the right upper part, and copying the https://github.com/sunnyomale442/greenwood-library-website.git () link and pasting it on the terminal in front of the below command to clone the rpository.

hp@DESKTOP-US68L7F MINGW64 ~/Desktop/greenwood-library-website
$ git clone https://github.com/sunnyomale442/greenwood-library-website.git
Cloning into 'greenwood-library-website'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

I went ahead and moved into the folder, creating four files namely home.html,events.html, contact_us.html, about us.html and checking my git status using this command below:

hp@DESKTOP-US68L7F MINGW64 ~/Desktop/greenwood-library-website
$ cd greenwood-library-website

hp@DESKTOP-US68L7F MINGW64 ~/Desktop/greenwood-library-website/greenwood-library-website (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

hp@DESKTOP-US68L7F MINGW64 ~/Desktop/greenwood-library-website/greenwood-library-website (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        about_us.html
        contact_us.html
        events.html
        home.html

nothing added to commit but untracked files present (use "git add" to track)

Contents were added to all the four files and saved with CTrl S the gid add and the status was checked to ensure the files have been commited and its colours are green. The command was given below :

hp@DESKTOP-US68L7F MINGW64 ~/Desktop/greenwood-library-website/greenwood-library-website (main)
$ git add .

hp@DESKTOP-US68L7F MINGW64 ~/Desktop/greenwood-library-website/greenwood-library-website (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about_us.html
        new file:   contact_us.html
        new file:   events.html
        new file:   home.html

I proceeded and commited the files and push it to the remote repository bu using the command below:

hp@DESKTOP-US68L7F MINGW64 ~/Desktop/greenwood-library-website/greenwood-library-website (main)
$ git commit -m " morgans first commit"
[main c9dc0e1]  morgans first commit
 4 files changed, 4 insertions(+)
 create mode 100644 about_us.html
 create mode 100644 contact_us.html
 create mode 100644 events.html
 create mode 100644 home.html

hp@DESKTOP-US68L7F MINGW64 ~/Desktop/greenwood-library-website/greenwood-library-website (main)
$ git push -u origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 597 bytes | 119.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/sunnyomale442/greenwood-library-website.git
   1a8761f..c9dc0e1  main -> main
branch 'main' set up to track 'origin/main'.

MORGAN'S TASK

A new branch for MORGAN was created named add-book-reviews, and a new file was created called book_reviews.html, contents were added and the file was saved. The staus was also checked and the files were added, commited and pushed to the main repository using the command below:


hp@DESKTOP-US68L7F MINGW64 ~/Desktop/greenwood-library-website/greenwood-library-website (main)
$ git checkout -b add-book-reviews
Switched to a new branch 'add-book-reviews'

hp@DESKTOP-US68L7F MINGW64 ~/Desktop/greenwood-library-website/greenwood-library-website (add-book-reviews)
$ git status
On branch add-book-reviews
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        book_reviews.html

nothing added to commit but untracked files present (use "git add" to track)     

hp@DESKTOP-US68L7F MINGW64 ~/Desktop/greenwood-library-website/greenwood-library-website (add-book-reviews)
$ git add .

hp@DESKTOP-US68L7F MINGW64 ~/Desktop/greenwood-library-website/greenwood-library-website (add-book-reviews)
$ git commit -m " add-book-reviews section"
[add-book-reviews 3ea4e58]  add-book-reviews section
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 book_reviews.html

hp@DESKTOP-US68L7F MINGW64 ~/Desktop/greenwood-library-website/greenwood-library-website (add-book-reviews)
$ git push origin add-book-reviews
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 284 bytes | 142.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'add-book-reviews' on GitHub by visiting:      
remote:      https://github.com/sunnyomale442/greenwood-library-website/pull/new/add-book-reviews
remote:
To https://github.com/sunnyomale442/greenwood-library-website.git
 * [new branch]      add-book-reviews -> add-book-reviews


I switched from MORGAN'S BRANCH to main using the the command below and wen to Github and created a PULL REQUEST by selecting the add-book-review under the MAIN on gitHub and clicked on creat pull rquest, added a comment on the description and clicked MERGE PULL REQUEST and also CONFIRM PULL REQUEST.

hp@DESKTOP-US68L7F MINGW64 ~/Desktop/greenwood-library-website/greenwood-library-website (add-book-reviews)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.


JAMIE'S TASK

 # I created a branch for Jamie (update-events) and switched to the new branch using the command below:

 hp@DESKTOP-US68L7F MINGW64 ~/Desktop/greenwood-library-website (main)
$ git checkout -b update-events
Switched to a new branch 'update-events'

# I added a new file named events_html and added content to the file and saved it, stage the files, commit and push the files to remote repository using the following commands below:

hp@DESKTOP-US68L7F MINGW64 ~/Desktop/greenwood-library-website/greenwood-library-website (main)
$  git checkout -b update-events
Switched to a new branch 'update-events'

hp@DESKTOP-US68L7F MINGW64 ~/Desktop/greenwood-library-website/greenwood-library-website (update-events)
$ git add .

hp@DESKTOP-US68L7F MINGW64 ~/Desktop/greenwood-library-website/greenwood-library-website (update-events)
$ git commit -m " update-events section"
[update-events 6e47489]  update-events section
 1 file changed, 1 insertion(+)
 create mode 100644 update_reviews.html

hp@DESKTOP-US68L7F MINGW64 ~/Desktop/greenwood-library-website/greenwood-library-website (update-events)
$ git push origin update-events
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 337 bytes | 168.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'update-events' on GitHub by visiting:
remote:      https://github.com/sunnyomale442/greenwood-library-website/pull/new/update-events
remote:
To https://github.com/sunnyomale442/greenwood-library-website.git

 * [new branch]      update-events -> update-events


I finally switched from JAMIE'S BRANCH to main using the the command git checkout main seen below and went to Github and created a PULL REQUEST by selecting the update-events under the MAIN on gitHub and clicked on creat pull rquest, added a comment on the description and clicked MERGE PULL REQUEST and also CONFIRM PULL REQUEST.

hp@DESKTOP-US68L7F MINGW64 ~/Desktop/greenwood-library-website/greenwood-library-website (update-events)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

hp@DESKTOP-US68L7F MINGW64 ~/Desktop/greenwood-library-website/greenwood-library-website (main)

This marks the end to the project..


