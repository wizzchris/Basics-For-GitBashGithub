Git is version control
It allows you to save changes via a timeline

Git Add - Allows you to add the files that you are ready to commit
Git Commit -m 'name' - Allows you to commit to the changes, adds a new point in the timeline called name
Git status - Shows you what is changed in the git timeline
Git push <remote repo> <branch> - Pushes the git branch to the remote repo ie github from the current branch ie master
Git remote --v - Shows you the remotes you are connected to
Git logs - Shows the log of all the points in the timeline, ie all the commits
Git init - Starts the timeline of the git in the directory

Creating SSH key
ssh-keygen -t rsa -b 4096 -C "your_email@example.com" - This creates the SSH key with the email as a label
eval $(ssh-agent -s) - Starts the ssh in the background
ssh-add ~/.ssh/id_rsa - adds the key to the SSH
clip < ~/.ssh/id_rsa.pub - copys the key to clipboard
