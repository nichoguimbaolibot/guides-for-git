generating a new ssh key
- $ ssh-keygen -t rsa -b 4096 -C "your_email@example.com"


adding the new ssh key to the agent 
- $eval "$(ssh-agent -s)"
- ssh-add `${directory_of_ssh)`
