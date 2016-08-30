# phase-0-gps-1

506  mkdir gps1.1
- Make a directory to put the contents of the Github repo into

507  cd gps1.1/
- Move to directory

508  git clone https://github.com/alealejandro/phase-0-gps-1.git
- Clone repo into directory from Github

509  touch awesome_page.md
- Create new file

510  git add awesome_page.md
- Stage awesome_page.md for commit

511  ls
512  rm awesome_page.md 
- Made a mistake, wasn't in correct git repo
- Deleted new file

513  cd phase-0-gps-1/
- Changed into correct directory

514  touch awesome_page.md
- Create new file

515  git add awesome_page.md
- Stage awesome_page.md for commit

516  git commit -m "first commit"
- Commit awesome_page.md

517  git push origin master
- Pushing master branch into Github repo <Github Dir><Branch from local>

518  git checkout -b add-command-log
- Made feature branch 

519  subl README.md 
- Made changes
