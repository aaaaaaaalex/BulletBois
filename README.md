# Gamedev Group Project

## Contributing

### Making a Commit

To contribute to this repo, first clone it locally...
```
git clone https://github.com/aaaaaaaalex/gamedev_group_project.git
```

Then make a branch off develop for whatever feature/work you're contributing to:
```
git checkout develop && git checkout -b "branch-name-here--make-it-somewhat-descriptive"
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

### Branch Structure

The `master` branch will contain the latest version of our project - every merge into this branch represents a new version/release if we break our game and aren't sure how, but need to deliver our project, we can simply roll this branch back one merge, and it'll work again.

The `develop` branch is the branch that you should merge your new features into once we've all reviewed them as Pull Requests - this way, we can use `develop` to integration-test new features, and when `develop` is stable, we can 'release' it by merging into `master`. 


**Make sure to clean intermediate files and built files before committing code, a bloated repo will take *literally* hours to clone**.

### Merging a new feature
As described above, your new feature, once ready, should be merged into the `develop` branch, so that it can be integration-tested with other merged features. To merge your feature, open a pull request on Github, **dont use `git merge` locally**. Make sure you're merging your changes into the right branch (develop), and once somone has reviewed your work, merge it in (if you want to keep the Git history on Develop super-clean, you can choose Squash & Merge, but if you'd prefer your individual commits to show up on the history for contributions metrics, merge regularly).
