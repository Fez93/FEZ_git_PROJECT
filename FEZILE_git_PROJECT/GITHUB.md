fezile@fezile-HP-15-Notebook-PC:~/git-basic-exercises$ git remote add origin https://github.com/Fez93/git-basic-exercises.git
fezile@fezile-HP-15-Notebook-PC:~/git-basic-exercises$ git push -u origin master

1.
fezile@fezile-HP-15-Notebook-PC:~/git-basic-exercises$ git push -u origin milkshake-flavour


							PULLING AND REMOTES

1.
fezile@fezile-HP-15-Notebook-PC:~/git-basic-exercises$ cd ../

2.
https://github.com/Umuzi-org/tech-department

3.
4.

5.
fezile@fezile-HP-15-Notebook-PC:~$ git clone https://github.com/Umuzi-org/tech-department.git

6.
fezile@fezile-HP-15-Notebook-PC:~$ cd tech-department

7.
fezile@fezile-HP-15-Notebook-PC:~/tech-department$ git branch
fezile@fezile-HP-15-Notebook-PC:~/tech-department$ git log

8.
fezile@fezile-HP-15-Notebook-PC:~/tech-department$ git branch -a

9.


					MULTIPLE REPOS

1.

2.
fezile@fezile-HP-15-Notebook-PC:~$ cd git-basic-exercises/
fezile@fezile-HP-15-Notebook-PC:~/git-basic-exercises$ git log

3.
fezile@fezile-HP-15-Notebook-PC:~/git-basic-exercises$ cd
fezile@fezile-HP-15-Notebook-PC:~$ mkdir this-will-be-another-repo

4.
fezile@fezile-HP-15-Notebook-PC:~$ cd this-will-be-another-repo
fezile@fezile-HP-15-Notebook-PC:~/this-will-be-another-repo$ git init

5.
fezile@fezile-HP-15-Notebook-PC:~/this-will-be-another-repo$ touch README.md
fezile@fezile-HP-15-Notebook-PC:~/this-will-be-another-repo$ git add README.md
fezile@fezile-HP-15-Notebook-PC:~/this-will-be-another-repo$ git commit -m "1st commit on TWBAR"

6.
fezile@fezile-HP-15-Notebook-PC:~$ cd git-basic-exercises 
fezile@fezile-HP-15-Notebook-PC:~/git-basic-exercises$ git log


					GITIGNORE
1.
fezile@fezile-HP-15-Notebook-PC:~/git-basic-exercises$ touch ignore-me.db

2.
fezile@fezile-HP-15-Notebook-PC:~/git-basic-exercises$ git status

3.
fezile@fezile-HP-15-Notebook-PC:~/git-basic-exercises$ nano .gitignore

4.
5.
fezile@fezile-HP-15-Notebook-PC:~/git-basic-exercises$ git status

6.
fezile@fezile-HP-15-Notebook-PC:~/git-basic-exercises$ mkdir large-directory-that-should-be-local-only

7.
fezile@fezile-HP-15-Notebook-PC:~/git-basic-exercises$ cd large-directory-that-should-be-local-only
fezile@fezile-HP-15-Notebook-PC:~/git-basic-exercises/large-directory-that-should-be-local-only$ nano README.md

8.
fezile@fezile-HP-15-Notebook-PC:~/git-basic-exercises/large-directory-that-should-be-local-only$ cd ..
fezile@fezile-HP-15-Notebook-PC:~/git-basic-exercises$ git status

9.
fezile@fezile-HP-15-Notebook-PC:~/git-basic-exercises$ nano .gitignore

10.
fezile@fezile-HP-15-Notebook-PC:~/git-basic-exercises$ git status


