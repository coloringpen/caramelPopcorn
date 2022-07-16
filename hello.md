# hello git

## git 명령어 요약

clone : copying remote repository(github) to my computer
add : adding worked file on stage
commit : save. can make commit(=save) with uploaded files on the stage area
push : uploading commit(saving record) to remote repository

## restoring file

if I want to restore certain file's content to last commit,

1. select the file
2. select 'discard hunk' on sourcetree

## modifying branch

branch : use when you want to make different staring points. to make modification maintaining prior works.

you will get error if you choose different starting point when you try to make modification on a file

branch is a virtual workspace

work with one branch(current branch, head branch) at a time

checkout : to go back to certain branch(or commit)
checkout in sourcetree : just double-click the branch name

## merging 1

- if there's no modification on head branch
- and a branch targeted to merge started from the head
- easy to merge both = fast-forward

## merging 2

- extra commit on head branch
- need 'real' merging
- it is the best if there is no 'crash', but let's not panic even though there it is:)

## solving crash

- important! don't panic!
