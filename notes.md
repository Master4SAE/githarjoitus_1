sohaibebrahimi@Sohaibs-MacBook-Pro git harjoitus % git clone https://github.com/mattpe/git-intro.git
Cloning into 'git-intro'...
remote: Enumerating objects: 77, done.
remote: Counting objects: 100% (27/27), done.
remote: Compressing objects: 100% (22/22), done.
remote: Total 77 (delta 10), reused 15 (delta 4), pack-reused 50
Receiving objects: 100% (77/77), 421.89 KiB | 3.46 MiB/s, done.
Resolving deltas: 100% (35/35), done.
sohaibebrahimi@Sohaibs-MacBook-Pro git harjoitus % cd git-intro
sohaibebrahimi@Sohaibs-MacBook-Pro git-intro % git remote remove 
origin
sohaibebrahimi@Sohaibs-MacBook-Pro git-intro % git remote add origin https://github.com/Master4SAE/githarjoitus_1.git
git branch -M main
git push -u origin main
Enumerating objects: 71, done.
Counting objects: 100% (71/71), done.
Delta compression using up to 4 threads
Compressing objects: 100% (38/38), done.
Writing objects: 100% (71/71), 420.02 KiB | 105.00 MiB/s, done.
Total 71 (delta 30), reused 70 (delta 30), pack-reused 0
remote: Resolving deltas: 100% (30/30), done.
To https://github.com/Master4SAE/githarjoitus_1.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
sohaibebrahimi@Sohaibs-MacBook-Pro git-intro % history
  560  git commit 
  561  git log
  562  git checkout sae
  563  git log
  564  git push
  565  git pul
  566  git pull
  567  git pull
  568  git clone https://github.com/mattpe/git-intro.git
  569  git remote 
  570  git remote help
  571  git add origin https://github.com/Master4SAE/githarjoitus.git
  572  git clone https://github.com/mattpe/git-intro.git
  573  cd git-intro
  574  git remote remove origin
  575  git remote add origin https://github.com/Master4SAE/githarjoitus_1.git\ngit branch -M main\ngit push -u origin main