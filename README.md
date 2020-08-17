# MergeExamples

- git checkout -b feature1
- git add .
- git commit -m "First feature"
- git push origin feature1

- git checkout master
- git merge feature1
- git push origin master

- git checkout -b feature2
- git add .
- git commit -m "Second feature part1"
- git push origin feature2

- git checkout -b hotfix
- git add .
- git commit -m "hotfix relase"
- git push origin hotfix
- git checkout master
- git merge hotfix
- git add .
- git commit -m "Hotfix merged into master"
- git push origin master

- git checkout master
- git merge feature2
- (Conflicts Solver)
- git add .
- git commit -m "Second feature part2 with hotfix"
- git push origin master