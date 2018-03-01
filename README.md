# GitHub Contribution Graph

![Heat Map Example](https://github.com/LambdaSchool/Code-Review-Checklist/raw/master/img/heatmap.png)

## If you'd like your work to count on your GitHub contribution graph, do the following:

1. Create a new empty repository with the name of the project. If you
   want it to match, rename or delete your GitHub repo. Don't worry,
   your local copy will be safe.

![Select "NEW repository"](https://github.com/LambdaSchool/Code-Review-Checklist/raw/master/img/select-New-repository.png)
![CREATE the new repository](https://github.com/LambdaSchool/Code-Review-Checklist/raw/master/img/create-new-repository.png)
![COPY the new repository's URL](https://github.com/LambdaSchool/Code-Review-Checklist/raw/master/img/copy-new-repo-URL.png)

2. Add the new empty repo as a new remote to your local git repository.

```console
$  git remote -v
   origin  https://github.com/LambdaSchool-PairStudentA/Preprocessing-I.git (fetch)
   origin  https://github.com/LambdaSchool-PairStudentA/Preprocessing-I.git (push)
$  git remote set-url origin https://github.com/mixelpixel/Preprocessing-I.git
$  git remote -v
   origin  https://github.com/mixelpixel/Preprocessing-I.git (fetch)
   origin  https://github.com/mixelpixel/Preprocessing-I.git (push)
```

3. Push the project to the new repo.

```console
$  git push
   Counting objects: 111, done.
   Delta compression using up to 4 threads.
   Compressing objects: 100% (77/77), done.
   Writing objects: 100% (111/111), 594.93 KiB | 45.76 MiB/s, done.
   Total 111 (delta 27), reused 111 (delta 27)
   remote: Resolving deltas: 100% (27/27), done.
   To https://github.com/mixelpixel/Preprocessing-I.git
   * [new branch]      master -> master
```

![Local repository pushed to StudentB's GitHub repository](https://github.com/LambdaSchool/Code-Review-Checklist/raw/master/img/local-repo-pushed-to-new-GH-repo.png)

4. Optionally, delete the old GitHub repo.

![Select the SETTINGS tab](https://github.com/LambdaSchool/Code-Review-Checklist/raw/master/img/select-the-project-Settings-tab.png)

![SCROLL down to the DANGER ZONE](https://github.com/LambdaSchool/Code-Review-Checklist/raw/master/img/scroll-down-to-the-bottom.png)

[![DELETE this repository](https://github.com/LambdaSchool/Code-Review-Checklist/raw/master/img/THE-DANGER-ZONE.png)](https://youtu.be/siwpn14IE7E)

![Enter the PROJECT name and press the BIG RED BUTTON](https://github.com/LambdaSchool/Code-Review-Checklist/raw/master/img/enter-the-project-name.png)
