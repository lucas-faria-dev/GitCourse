# GitCourse
This tutorial is to learn to use the git bash
-Let's see how it goes.
## Subheader
This is a change
# Command git init

# Command git add
git add .
git add -A

# Command git commit
git commit -m "Message header" -m "Message body"

# SSH Keys
ssh-keygen -t rsa  -b 4096 -C "email@test.com"
-t (encryption type)
-b (encryption strength)
-C ( github email address)

$ ssh-keygen -t ed25519 -C "your_email@example.com"

https://docs.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

Only share your KeyName.pub key.
cat KeyName.pub to see your public key.

# Command git Push
git push origin master