Complete a merge that requires conflicts to be resolved and briefly (in just a sentence or two) explain how the conflict arose and how you resolved it. Provide a link to the commit.

For this I created my own git repository locally using git init and created my own conflict with txt files commiting different txt in the main and branch. After I had created the conflict and failed the merge, I used the cat cmd in terminal and to resolve just removed the txt block and head tag.
========

git-stash

git stash is used when you want to save your changes allowing you to jump back to the 'head' commit, it is essentially a push and your file will be stored in a WIP folder on your branchname. Your stashed files can be seen with the 'git stash list' cmd, you can inspect them with 'git stash show' and you can restore them with 'git stash apply'. 

I think it could be pretty useful with experimenting or if you need to save changes but are not wanting to commit

