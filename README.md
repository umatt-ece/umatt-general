# UMATT General
All _projects_, _issues_, and _resources_ in one location.

## Quick Links
- [Project Planning](https://github.com/umatt-ece/umatt-general/tree/main/project-planning)
- [Resources](https://github.com/umatt-ece/umatt-general/tree/main/resources)

## Local Setup
> For more detailed information about setting up repositories locally, checkout our [git tutorial](). Alternatively, if you perfer to you the GitHub interface, most actions will still be possible. You can check out our [GitHub]() tutorial for more information on that.

You can _clone_ this repository to your local computer. This will allow all files to be accessible offline and in a familiar file-system format.
```shell
git clone git@github.com:umatt-ece/umatt.git
git submodule init
git submodule update
```

To update your local repository with the latest changes, you can _pull_ any new commits from GitHub. It is a good idea to do this before modifying any files locally.
```shell
git pull
git submodule foreach pull
```

If you've made changes to folders/files, you can _commit_ those changes and _push_ them to GitHub. 
```shell
git add --all
git commit --all --message "provide a description of the changes made"
git push
git submodule foreach push
```
