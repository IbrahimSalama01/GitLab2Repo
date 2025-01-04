Remove lcoal Branch => **git branch -d 'name_of_the_branch'** _while you are at another branch_  
Remove remote Branch => **git push  :'name_of_the_branch'** 

lightweight tags are just pointers for a specific commit specifying that this commit is important _a feature is ready or this version is ready for release_ 
the annonated tags aren't just pointers they are objects storing the name of the creator, his email, the date, a tagging message and the checksum of the commit 


#when to use Rebase 
-> when the chnages made in the base branch should have been done before the new branch  in the project timeline  _ you change the history of the commits_.
-> when you make changes to the base branch that you need in the new branch.

#list tags:
git tag
git tag -l

#remove tags:
git tag -d 'tag_name' -> _local tag_.
git push origin -d 'tag_name' -> _remote tag_.

![Bo7a](https://pbs.twimg.com/media/DzJiJtqWkAAmZlM.jpg)
