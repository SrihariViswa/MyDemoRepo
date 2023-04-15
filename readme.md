After SSH is Set from HTTPS..HTTPS is giving TLS error
Did below in GitBash
Change your remote's URL from HTTPS to SSH with the 'git remote set-url command'
command: git remote set-url origin git@github.com:USERNAME/REPOSITORY.git \n
command: git remote set-url origin git@github.com:SrihariViswa/MyDemoRepo.git \n
Here, 'SrihariViswa' is the Git USERNAME & 'MyDemoRepo' is the Repository name used,
When execute this command in the local Git folder then the command 'Git Push origin master' will push the committed code to this set Repo ( i.e MyDemoRepo here).

git remote -v ; 'will show the connected git url/path'
git global --list ; 'will show the global settings set'
git add <filename> ; 'add single file to staging'
git add * ; 'add all files to staging at same time'
git commit -m "commit message" ; 'to commit all staged files'
git push origin master ; 'To push all committed files to github Repo. To which GitHub Username and To which Repo are Set by above command /ni.e command: git remote set-url origin git@github.com:USERNAME/REPOSITORY.git
Eg: git remote set-url origin git@github.com:SrihariViswa/MyDemoRepo.git'
