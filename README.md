# git-hooks
some samples of pre-commit hooks

Dear User,
hooks are stored in the actual project directory (above the .git directory)
To install the hook, you can either create a symlink to it in .git/hooks, or you can simply copy and paste it into the .git/hooks directory whenever the hook is updated.

Steps:
1.Clone the public repo in you local machine
2.Copy hookfiles ie pre-commit and commit-msg from project directory to .git/hooks/
Command : 
cd projectdirectory
cp pre-commit commit-msg .git/hooks/ 
3.Try commiting a new file with various usecases to validate hooks.


