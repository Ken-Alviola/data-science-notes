ssh-keygen -p -f ~/.ssh/id_rsa
New
1:43
If you do git push anbd you get a prompt to enter your github.com username then your github.com password
1:44
^ only for the github username prompt f
1:44
git remote remove origin
1:44
Then go to your repository in GitHub
1:45
click the green :Code” button
1:45
and copy the SSH clone address
1:45
then go back to your terminal and type git remote add origin  followed by pasting the remote that looks like git@github.com:CodeupClassroom/easley-now-we-know.git that you just copied (but for your own repository, not this specific one)