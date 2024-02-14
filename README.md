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
git push origin master.



eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519
git clone git@github.com:lucasfarias300/Outsystems.git
git pull git@github.com:lucasfarias300/Outsystems.git <branch>
git push git@github.com:lucasfarias300/Outsystems.git <branch>
git push git push <remote> <branch>
git config --global user.signingkey 5484yourkey19283
git push --set-upstream origin 2021-07-19


git switch -c <branch> --track <remote>/<branch>
ref:   https://bluecast.tech/blog/git-switch-branch/#:~:text=git%20switch%20to%20remote%20branch.%20To%20switch%20to,the%20latest%20remote%20updates%20%28including%20the%20remote%20branches%29.

git switch -c new-documentation-dev --track origin/new-documentation-dev

 git checkout -t origin/new-documentation-qa
 git switch new-documentation-dev
