Basic Linux Commands
	- cd - change directory
	- man - open manual for most of the commands
	- whoami - display the name of the user
	- clear - clear console whith scroll history
	- pwd - print current working directory
	- ls - display all file and folder list

Basic Git commands
	
	
Git log
By default means without any flags git log command will show will SHA, author, date and commit message.

git log --oneline will show you one commit per line, the seven characters of SHA, the commit message.
git log --stat will show you:
	the files that were modified in each commit
	the number of lines added or removed
	a summary line with the total number of files and lines changed
git log --oneline --graph works best if you want to have a look at the project in a brief way. It is not good for big and large codebase. It becomes chaos.
