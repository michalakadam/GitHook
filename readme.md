# Git precommit hook script

### Requirements

1. Project with git repository initialize.
2. Maven structure and pom included.

### How do I implement this hook

1. Copy this script
2. Go to your project folder
3. Type: cd .git/hooks
4. Open file pre-commit.sample in a text editor
5. ctrl+a, ctrl+v
6. Save pre-commit.sample
7. Type: mv pre-commit.sample pre-commit

READY!

Everytime you commit something in this repositry, precommit hook will do its job: build Maven project and see if the build was successful. 
