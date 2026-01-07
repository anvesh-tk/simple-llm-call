1. C:\Users\anves\virtual_environments>python -m venv firstllmproject_env

2. C:\Users\anves\virtual_environments>cd firstllmproject_env

3. C:\Users\anves\virtual_environments\firstllmproject_env>cd Scripts

4. C:\Users\anves\virtual_environments\firstllmproject_env\Scripts>activate

5. (firstllmproject_env) C:\Users\anves\virtual_environments\firstllmproject_env\Scripts>cd C:\Users\anves\FirstLLMProject

# It Opens into VS IDM
6. (firstllmproject_env) C:\Users\anves\FirstLLMProject>code . 


# git commands for first time.
1. (firstllmproject_env) C:\Users\anves\FirstLLMProject>git init
Initialized empty Git repository in C:/Users/anves/FirstLLMProject/.git/

2. (firstllmproject_env) C:\Users\anves\FirstLLMProject>git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

# Add files in Visuval Studio
3. (firstllmproject_env) C:\Users\anves\FirstLLMProject>git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        requirements.txt

nothing added to commit but untracked files present (use "git add" to track)

4. (firstllmproject_env) C:\Users\anves\FirstLLMProject>git add .

5. (firstllmproject_env) C:\Users\anves\FirstLLMProject>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   requirements.txt

# While doing first time we get below issue, setup issue 
6. (firstllmproject_env) C:\Users\anves\FirstLLMProject>git commit -m "added requirements.txt file"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'anvesh@Adarsh.(none)')

(firstllmproject_env) C:\Users\anves\FirstLLMProject> git config --global user.email "anvesh.bigdata08@gmail.com"

(firstllmproject_env) C:\Users\anves\FirstLLMProject>git config --global user.name "anvesh tk"

7. (firstllmproject_env) C:\Users\anves\FirstLLMProject>git commit -m "added requirements.txt file"
[master (root-commit) 9b4e2f7] added requirements.txt file
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 requirements.txt

 # Connect your local to Github copy and paste origin url
8. (firstllmproject_env) C:\Users\anves\FirstLLMProject>git remote add origin https://github.com/anvesh-tk/simple-llm-call.git

9. (firstllmproject_env) C:\Users\anves\FirstLLMProject>git branch
* master

10. (firstllmproject_env) C:\Users\anves\FirstLLMProject>git branch -M main

11. (firstllmproject_env) C:\Users\anves\FirstLLMProject>git branch
* main

12. (firstllmproject_env) C:\Users\anves\FirstLLMProject>git push -u origin main


# Now Write code in main.py

# Before execute install transformers torch

(firstllmproject_env) C:\Users\anves\FirstLLMProject>pip install transformers torch

(firstllmproject_env) C:\Users\anves\FirstLLMProject>python main.py

# Will generate below output

[{'generated_text': "AI is the future because, while it is not easy, it is also easier and more convenient.\n\nThe project is free and open source. You can use any version of the project on Github, like this one.\nAbout Me\nA lot of people I know are going to be a bit of a geek, when I get a chance to talk to them about it. Here are some of the things I learned from working with me:\nIt's not easy to make a project that you don't want to work with and it's harder to work with on a project that you don't want to work with. That would be better if you were not able to go back and find something new like a good website.\nIf you are interested in getting started with the project, this is the first step. If you are interested in learning how to make an interactive website, this is the first step. If you are interested in making a interactive website, this is the first step. If you are interested in learning how to make an interactive website, this is the first step. If you are interested in working with me, this is the first step. If you are interested in learning how to make an interactive website, this is the first step. If you are interested in learning how to"}]

# Commit code to GIT
(firstllmproject_env) C:\Users\anves\FirstLLMProject>git status

(firstllmproject_env) C:\Users\anves\FirstLLMProject>gid add .

(firstllmproject_env) C:\Users\anves\FirstLLMProject>git status
(firstllmproject_env) C:\Users\anves\FirstLLMProject>git branch
(firstllmproject_env) C:\Users\anves\FirstLLMProject>git push
(firstllmproject_env) C:\Users\anves\FirstLLMProject>