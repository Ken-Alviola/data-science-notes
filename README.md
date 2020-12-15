ssh-keygen -p -f ~/.ssh/id_rsa


If you do git push anbd you get a prompt to enter your github.com username then your github.com password

^ only for the github username prompt f

git remote remove origin

Then go to your repository in GitHub

click the green :Code” button

and copy the SSH clone address

then go back to your terminal and type git remote add origin  followed by pasting the remote that looks like git@github.com:CodeupClassroom/easley-now-we-know.git that you just copied (but for your own repository, not this specific one)