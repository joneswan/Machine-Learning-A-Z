# Machine-Learning-A-Z

[Refernce](https://stackoverflow.com/questions/1274057/how-to-make-git-forget-about-a-file-that-was-tracked-but-is-now-in-gitignore)

# Remove index (cache) from remote
git rm -r --cached ./Part\ 8\ -\ Deep\ Learning/Section\ 40\ -\ Convolutional\ Neural\ Networks\ \(CNN\)/dataset/

git rm -r --cached ./.RData

git rm -r --cached ./.Rhistory

git rm -r --cached ./.spyproject/

git rm -r --cached ./.Rproj.user/

git rm -r --cached ./Machine-Learning-A-Z.Rproj

# Update .gitignore ()
./Part\ 8\ -\ Deep\ Learning/Section\ 40\ -\ Convolutional\ Neural\ Networks\ \(CNN\)/dataset/
./.RData
./.Rhistory
./.spyproject/
./.Rproj.user/
./Machine-Learning-A-Z.Rproj

# Commit
git commit -am "Remove ignored files"

# Update remote
git push origin master
