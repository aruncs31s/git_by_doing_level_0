# Level 0

Task: Getting a gthub repository the right way

> [!IMPORTANT]
> You need to get this github repository in you computer and run the following
>
> ```bash
> bash check.sh
> ```
>
> If you see the following message read the github page again
>
> ```
> Faild , Try Again
> READ the webpage again
> ```

## Git Clone 
>[!Note]
> **Too long to read?**
>It creates a local copy of a remote Git repository

You ever heard the term **distributed**? , it something that spread accross or have meany coppies or meany different forms of itself across meany holders. 
- What you mean by holders?
- What i mean by copies?

When trying out  `git` for the first time it will not make sence , like why do someone want to use commands to download some files , when they can just hit the `Download` button and be done with it , yes infact if you just want the project and no git features like the history and view commits (will explain latter) you can just do that. 
This is why you want to clone a github repository
1. Its the correct way of obtaining a git repository 
2. You want to see the commit list
3. You want to contribute that project
and there are several other reasons.

### History 
Git stores commits as some points in time where you can go to that point and explore what they have done upto that point

For example if there is a commit named 2024 and it read something like this 
```
Commit for 2024 , this commit includes what we have done upto this point. 
```

this is a example image showing commits of this current repository ![git log](./git%20log.png) 
It contains the collowing commits 
1. Start , Made on 13-06-2025 , by Arun CS 
2. adding 1st task , the same day by Arun CS 
3. finished setup , same day by Arun CS
4. Delete test , same day by Arun CS

What can you understand or grasp from all his texts? 
1. Start 
Before this commit there was no repository itself , this is where everything started , the standard practice is to name this commit **Initial Commit**

**Initial Commit**: Initial commit is the first commit when you start doing a project, which may include inital code or something, in most projects it just be `README.md` file. 

2. Adding 1st task
It Specifies that i have added 1st task, its i can go on like this say if i added some other task , i will give it a commit message like "adding 2nd task" so , in short , commit message should shortly describe what you have done after one commit , still dont get it read the following. 

>[!Note]
> **How to right a proper commit message**
> In most of the project , you clone a `git` repository , and start wokring on it , and after you finished working , you want to save your work right ? and for that you need to commit what you have done and upload it to where you cloned the repository is from. And to make it more easy like giving a title to **what you have done** that does not have before , it might be fixing one bug or adding one feature , so you do something like this *fix: bug x* or *feat: new login feature* , or you can write what your mind tells you , but it should shortly describe what you have done , and its recommended to follow a pattern like putting `feat` infront of a git commit to specify its a feature.


## Hint:

- You can 'download', 'clone' the repo.
  to use clone type this in your cmd/terminal

```bash
git clone <the repocitory url>
```

eg:

```bash
git clone https://github.com/aruncs31s/level_0
```

- If you download code from GitHub, remember the word download, it does not downloads the `.git` folder

## Summary

- Repo: Repo Means a kind of folder, but it will have the .git folder.
- repo short for Repository
- "."(dot) infont of a folder means it's hidden
- When you download a repo from GitHub it will not contain the `.git` folder

> [!CAUTION]
> `Download` and `clone` are not same

## FAQ:

1. Why there is a dot(.) in front of the .git folder
   Ans: The . or dot, means it is a hidden folder.

2. Where will be the 'download' thing in the https://github.com site
   Ans: If you open a repository (from now on we call repository as repo)
   you will see a dropdown at the top right named "Code",
   click on that and then you will see two tabs "Local" and "CodeSpaces"
   and then you will see "Clone" and "Download Zip" option
