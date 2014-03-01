Test for Submodule2

Creating New Repository for New Project(New-Repo):-

1]mkdir New-Repo and add a file test.txt on local m/c

2]cd New-Repo

3]touch README.md(test.txt)

4]git init

5]git add README.md

6]git commit -m "first commit"

7]Go to Github.com and Create a new Repository With exact name as New-Repo and ---Uncheck the checkbox:- Initialize this repository with a README

8]Copy https://github.com/amolplay/New-Repo.git which is generated on next page

8]git remote add origin https://github.com/amolplay/New-Repo.git

8]git push origin master

9]Go to respective page and Reload(Refresh that page then u can see that New-Repo created with Test.txt)

where-- content of README.md file displaying on index page of each repository

==========
Push an existing repository from the command line

git remote add origin https://github.com/amolplay/New-Repo.git

git push origin master
