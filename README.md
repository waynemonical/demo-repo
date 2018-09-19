## Demo Repo ##

This is example text. I'm going to make a bunch of changes, then see if Git Bash notices with `git status`

Okay, that command returned clean, and that makes sense I guess. Right now I'm working in RStudio, so it would be crazy if Git somehow saw the work I was doing in some other program. I'm going to save this document with these new changes and then see if Git notices.

Oh my gosh it did! it says `modified: README.md` in adorably red text, but also, it says that I don't have any changes to commit. Here's my experiment. I'm going to save this file, then check on 'demo-repo' online, and what I should see is that it hasn't been changed at all. Then I'm going to use `git add README.md` and `git commit -m "second commit"` in order to save it to the origin repository on my computer. AND THEN I'm going to use `git push origin master` to get my changes online. I'm then going to check if the changes I made are online or not. I really hope they are.