# Day 7
Today we presenting the answer from question swap , we got question from team 6 the question is:

![image](https://user-images.githubusercontent.com/85722211/203807352-168d72f2-5116-40db-8185-012923da68db.png)

Rebase is one of two Git utilities that specializes in integrating changes from one branch onto another. The other change integration utility is git merge. Merge is always a forward moving change record. Alternatively, rebase has powerful history rewriting features.

Rebasing is the process of moving or combining a sequence of commits to a new base commit. Rebasing is most useful and easily visualized in the context of a feature branching workflow. The general process can be visualized as the following:

![image](https://user-images.githubusercontent.com/85722211/203808115-43510272-1b20-4d90-8871-667464570bcc.png)

From a content perspective, rebasing is changing the base of your branch from one commit to another making it appear as if you'd created your branch from a different commit. Internally, Git accomplishes this by creating new commits and applying them to the specified base. It's very important to understand that even though the branch looks the same, it's composed of entirely new commits.

### what i've done this week
this week we trying to make api using node.js
our task is to make api for posts and comments

in this task we make folder sturcture like this : 

![image](https://user-images.githubusercontent.com/85722211/203808865-c4734668-1bf0-4dd2-b82c-0d3a8d06310c.png)

1. app.js for run the server
2. schemas folder for seting the database models
3. routes for endpoint base on schema

for deploying to live server we need to add start scripts in package.json 

![image](https://user-images.githubusercontent.com/85722211/203809423-c4b227ec-3ba0-4b48-b13a-624e56b23d7b.png)

and if we use heroku we need to define port in env 

![image](https://user-images.githubusercontent.com/85722211/203809547-304c2cd5-7d8b-4604-a483-ec5ad51ae306.png)

