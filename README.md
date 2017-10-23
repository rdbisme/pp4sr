You need to install [jq](https://stedolan.github.io/jq/)for correct diffing of notebooks with GIT 
and [git-lfs](https://git-lfs.github.com/).

Then add the `.gitconfig` to your local repo config
```
git config --local include.path ../.gitconfig
```

You need also to install RISE plugin for jupyter

