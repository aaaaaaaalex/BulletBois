# Gamedev Group Project

## Contributing
To contribute to this repo, first clone it locally...
```
git clone https://github.com/aaaaaaaalex/gamedev_group_project.git
```

Then make a branch for whatever feature/work you're contributing to:
```
git checkout -b "branch-name-here--make-it-somewhat-descriptive"
```

For every single change you make, add and commit it:
`git status` and `git diff` will confirm the changes you made, check these before every single commit or you might commit some unexpected crap and ruin everyone's day.

`git add .` will add all changes, you can also specify file paths if you only want to add a single changed file out of many: 
```
git add thing/otherthing/file
```

Finally, commit your change with a descriptive message:
```
git commit -m "here is my message - its describing all the useless shit I did :D "
```

The `master` branch will contain the latest version of our project - every merge into this branch represents a new version.
The `develop` branch is the branch that you should merge your new features into - it's used to integration-test new features, and is the only branch that you should merge into `master` from. **NEVER MERGE MASTER INTO DEVELOP, ONLY DEVELOP INTO MASTER, THIS WILL KEEP OUR GIT HISTORY CLEAN AND READABLE**

**Make sure to clean intermediate files and built files before committing code, a bloated repo will take *literally* hours to clone**.

