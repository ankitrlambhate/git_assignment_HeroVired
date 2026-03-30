# The repositiory contains 3 assignments
  1. CalculatorPlus 
  2. Git LFS
  3. Geometry Calculator 

# 1. CalculatorPlus:
      a. Created a dev branch using: git checkout -b dev
      b. Added calculator code with basic operations.
      c. Implemented a square root feature 
      d. Merged these changes with main branch using: git checkout main, git pull origin main, git merge dev, git push origin main, git tag -a v1.0 -m "Version 1 release of CalculatorPlus app", git push origin v1.0
      e. Adding the square root feature in a new square root feature branch: git checkout -b feature/sqrt
      f. Switching to dev branch to fix a bug in divide function: git checkout dev, git add CalculatorPlus.py, git commit -m "Fixed divide by zero bug", git push origin dev
      g. Updating the feature/sqrt branch with dev branch: git checkout feature/sqrt, git merge dev, git add CalculatorPlus.py, git commit -m "Added square root feature", git push origin feature/sqrt
      h. Creating pull request: git checkout feature/sqrt, git push -u origin feature/sqrt
      i. Merge changes to dev branch: git checkout dev, git pull origin dev, git merge feature/sqrt, git push origin dev
      j. Merging to main branch: git checkout main, git pull origin main, git merge dev, git push origin main
      k. Adding the final release tag: git tag -a v2.0 -m "Version 2 with sqrt feature and bug fix", git push origin v2.0
       
