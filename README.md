##Instructions

```
mkdir new-project
git init
echo "#README" > README.md
git add . 
git commit -am "init"
git checkout -b development
# nano README.md , add instructions, save
git commit -am "added instructions"
git merge development main
```
