# springazureappdemo
git command to commit to the project

https://zapier.com/blog/how-to-push-to-github/

go to directory project folder of spring boot:~/Downloads/spring-azure-demo-main/

enter following commands:
=========================
git clone https://github.com/srivathsansri23/springazureappdemo.git~

git add .

git commit -m "init commit"

git push origin main


other useful commands:
======================

https://www.theserverside.com/video/How-to-use-the-git-remote-add-origin-command-to-push-remotely#:~:text=Perform%20a%20git%20push%20to%20the%20remote&text=Make%20sure%20you%20specify%20the,with%20the%20git%20push%20command.

git remote add origin https://github.com/srivathsansri23/springazurewebappdemo.git

Changing remote origin:
=======================
git remote -v

``
#View existing remotes
origin  https://github.com/user/repo.git (fetch)
origin  https://github.com/user/repo.git (push)
``

git remote set-url origin https://github.com/user/repo2.git

``Change the 'origin' remote's URL``

git remote -v

``
#Verify new remote URL
#origin  https://github.com/user/repo2.git (fetch)
#origin  https://github.com/user/repo2.git (push)
``
