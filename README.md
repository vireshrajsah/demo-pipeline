# Read Me Test

### To check for current remote directories
```
git remote -v
```
### Setting up git
```
git init
```
### Setting new remote directory as 'origin'
```
git remote add origin https://github.com/vireshrajsah/demo-pipeline-2.git
```
### Setting new remote directory as 'demoold'
```
git remote add demoold https://github.com/vireshrajsah/demo-pipeline.git
```

### Pulling and merging demoold
```
git pull --allow-unrelated-histories demoold main From https://github.com/vireshrajsah/demo-pipeline
```
### Setting branch name
```
git branch -M main 
```
### Git add-commit
```
git add .
git commit -m "update"
```
### Git push to demoold
```
git push -u demoold main
```
