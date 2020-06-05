# gitconfig
> Speed up your development with a list of useful git aliases and shortcuts.

## Usage
```shell script
git clone git@github.com:davidecaruso/gitconfig.git && cd gitconfig
cp .gitconfig ~ && vi ~/.gitconfig
# Update "email" and "name" properties with yours
```

## TOC
| Alias         | Description                                                          | Parameters          |
|---------------|----------------------------------------------------------------------|---------------------|
| br            | Shortcut of `branch`                                                 | See `branch`        |
| st            | Shortcut of `status`                                                 | See `status`        |
| ci            | Shortcut of `commit`                                                 | See `commit`        |
| co            | Shortcut of `checkout`                                               | See `checkout`      |
| commend       | Shortcut of `commit --amend`                                         | --                  |
| l             | Show logs graph                                                      | See `log`           |
| f             | Fetch & prune                                                        | See `fetch`         |
| new           | Create a new branch                                                  | Branch name         |
| rename        | Rename the current branch name                                       | New branch name     |
| cp            | Checkout in a branch and pull from origin                            | Branch name         |
| cia           | Stage and commit all changes                                         | --                  |
| pa            | Push all branches and tags                                           | --                  |
| pp            | Pull & push the current branch                                       | --                  |
| sync          | Fetch from remote and pull master and develop                        | --                  |
| clear         | Clear all changes                                                    | --                  |
| untag         | Delete locally and remotely a tag                                    | Tag name            |
| unstage       | Remove from stage                                                    | File names          |
| uncommit      | Undo the last commit locally                                         | --                  |
| all-diffs     | All differences between two branches                                 | Two branch names    |
| new-diffs     | New file differences between two branches                            | Two branch names    |
| cop-diffs     | Copied file differences between two branches                         | Two branch names    |
| del-diffs     | Deleted file differences between two branches                        | Two branch names    |
| mod-diffs     | Modified file differences between two branches                       | Two branch names    |
| ren-diffs     | Renamed file differences between two branches                        | Two branch names    |
| reset-chmod   | Reset files permissions                                              | --                  |

## Author
[Davide Caruso](https://about.me/davidecaruso)

## License
Licensed under [MIT](LICENSE).
