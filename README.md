# GIT-HUB-LINKING SSH KEY 
Open Git Bash.

Paste the text below, substituting in your GitHub email address.

$ ssh-keygen -t ed25519 -C "your_email@example.com"
Note: If you are using a legacy system that doesn't support the Ed25519 algorithm, use:

$ ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
This creates a new SSH key, using the provided email as a label.

ssh -T git@github.com

# Attempts to ssh to GitHub
> Generating public/private algorithm key pair.
When you're prompted to "Enter a file in which to save the key," press Enter. This accepts the default file location.

> Enter a file in which to save the key (/c/Users/you/.ssh/id_algorithm):[Press enter]
At the prompt, type a secure passphrase. For more information, see "Working with SSH key passphrases."

> Enter passphrase (empty for no passphrase): [Type a passphrase]
> Enter same passphrase again: [Type passphrase again]
after that navigate to the specific folder that contains your ssh key , open with notepad . copy and paste in ssh key section 
