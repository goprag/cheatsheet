# cheatsheet for common git commands

# Squash 2 commits

    git rebase -i HEAD~2

    # Change later commits from pick to squash
    # if something goes wrong

    git rebase--edit-todo

    # if not happy
        
    git rebase --abort

# Change author email

    
    Update the email and name in .gitconfig
    or
    git commit --amend --author="jon.doe@example.com"
    
    git commit --amend --reset-author



 

    

