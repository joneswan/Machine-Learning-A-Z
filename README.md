# Machine-Learning-A-Z

[Refernce](https://stackoverflow.com/questions/1274057/how-to-make-git-forget-about-a-file-that-was-tracked-but-is-now-in-gitignore)

# Remove index (cache) from remote
git rm -r --cached ./Part\ 8\ -\ Deep\ Learning/Section\ 40\ -\ Convolutional\ Neural\ Networks\ \(CNN\)/dataset/

# Update .gitignore ()
./Part\ 8\ -\ Deep\ Learning/Section\ 40\ -\ Convolutional\ Neural\ Networks\ \(CNN\)/dataset/

# Commit
git commit -am "Remove ignored files"

# Update remote
git push origin master
