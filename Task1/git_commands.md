    1  clear
    2  cd D:
    3  cd Practice/AllSolution/
    4  git clone https://github.com/niteshghosh/cloudnloud-assesment.git
    5  cd cloudnloud-assesment/
    6  mkdir Task1
    7  cd Task1/
    8  touch README.md
    9  git status
   10  git add README.md
   11  git comment -m "ReadMe file added"
   12  git commit -m "ReadMe file added"
   13  git status
   14  git push -u origin master
   15  git branch dev
   16  git checkout dev
   17  touch test.txt
   18  git status
   19  git add -m "test file created as per steps"
   20  git add test.txt 
   21  git commit -m "test file created as per steps"
   22  git push -u origin dev
   23  git branch %USERNAME-new_feature
   24  git checkout %USERNAME-new_feature
   25  touch README.md
   26  git status
   27  touch .gitignore
   28  cat .gitignore
   29  git add .gitignore 
   30  git commit -m "adding git ignore file as per steps"
   31  git push -u origin %USERNAME-new_feature
   32  git branch
   33  git add README.md
   34  git commit -m "added content in README"
   35  git log
   36  git reset --soft HEAD~1
   37  git log
   38  git checkout master
   39  git checkout %USERNAME-new_feature
   40* 
   41  git log > log.txt
   42  git checkout master
   43  git add log.txt
   44  git branch --delete %USERNAME-new_feature
   45  git branch
   46  git push origin --delete %USERNAME-new_feature
   47  history > git_commands.md
