# Git config

List of git aliases.

## Usage
Copy the *.gitconfig* in your user root directory and edit **\[EMAIL\]** and **\[FULL_NAME\]** with your info.

## TOC
| Alias         | Parameters          | Description                                                          |
|---------------| ------------------- |----------------------------------------------------------------------|
| *co*          | See `checkout`      | Alias of *checkout* command.                                         |
| *br*          | See `branch`        | Alias of *branch* command.                                           |
| *ci*          | See `commit`        | Alias of *commit* command.                                           |
| *cia*         | --                  | Add all modifies to stage and commit commit.                         |
| *st*          | See `status`        | Alias of *status* command.                                           |
| *commend*     | --                  | Combine staged changes with the previous commit.                     |
| *unstage*     | None or file paths  | Unstage all changes.                                                 |
| *undo*        | --                  | Undo the previous un-pushed commit.                                  |
| *untag*       | Tag name            | Delete remotely a tag.                                               |
| *pushall*     | --                  | Push simultaneously all branches and tags.                           |
| *pp*          | --                  | Perform a push after a pull command.                                 |
| *amid*        | Two branch names    | Show affected files from differences between two given branch names. |
| *l*           | See `log`           | Show logs as graph.                                                  |
| *reset-chmod* | --                  | Reset files' permissions.                                            |
| *new*         | Branch name         | Create a new branch.                                                 |
| *rename*      | See `branch -m`     | Rename the current branch OR Reset files' permissions.               |
| *clear*       | --                  | Reset all changes, creations and deletions.                          |

## Author
[Davide Caruso](https://davidecaruso.github.io)

## License
Licensed under [MIT](LICENSE).