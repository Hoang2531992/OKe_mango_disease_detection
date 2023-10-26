# OKe_mango_disease_detection

https://gist.github.com/xirixiz/b6b0c6f4917ce17a90e00f9b60566278#copy-the-public-ssh-key-to-github
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account
https://www.freecodecamp.org/news/error-failed-to-push-some-refs-to-how-to-fix-in-git/

note: https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository

ssh-keygen -t rsa -C "hoang2531992@gmail.com"

macOS:

pbcopy < ~/.ssh/id_rsa.pub

Copy the public SSH key to GitHub
Copy the contents of the to your SSH keys to your GitHub account settings (https://github.com/settings/keys).

Test the SSH key:
ssh -T git@github.com

git add -A 

git commit -am "Update README.md"

** create new brand: (master) "https://www.freecodecamp.org/news/error-src-refspec-master-does-not-match-any-how-to-fix-in-git/"
You can create a remote master branch on a Git managed website (like GitHub) or you can do that directly from your terminal like this:

git checkout -b master

git push origin master    " have error: git pull --rebase origin main  or git pull --rebase origin master "

git push origin master
