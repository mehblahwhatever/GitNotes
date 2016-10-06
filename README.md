# GitNotes 

## Set up project
```
git init
echo FILE
git add FILE
git commit -m "first commit"
git remote add origin https://github.com/mehblahwhatever/GitNotes.git
git push -u origin master
```
## Make a commit
```
echo NEW_FILE
git add NEW_FILE
git commit -m "second commit"
git push -u origin master
```

## Switch to a new branch
```
git branch NEW_BRANCH
git checkout NEW_BRANCH
```

## Push a new branch
```
git push -u origin NEW_BRANCH
```

## Merge branch into master
```
git checkout master
git merge NEW_BRANCH
git push -u origin master
```

## Download copy of existing project (creates sub-folder)
```
git clone https://github.com/mehblahwhatever/GitNotes.git
```
