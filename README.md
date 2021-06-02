# tigconfig

The config I use for [tig](https://github.com/jonas/tig)

## Cheat sheet

### Staging view

| Command | Description                   |
| ------- | ----------------------------- |
| **D**   | Delete untracked file         |
| **!**   | Reset unstaged file           |
| **C**   | Commit all staged files       |
| **1**   | Stage one line                |
| **u**   | Stage file or stage one chunk |
| **+**   | Amend to previous commit      |
| **P**   | Push                          |
| **I**   | Put file in gitignore         |
| **S**   | Stash unstaged files          |

### History view

| Command | Description                   |
| ------- | ----------------------------- |
| **H**   | Open commit on github.com     |
| **B**   | Open commit on bitbucket.org  |

## Use cases

### Branches

#### Checkout

- Press `r` to go the `refs` view
- Press `C` to checkout branch
- Press `enter` to confirm

#### Create

- Press `r` to go the `refs` view
- Press `n` to create branch
- Enter branch name and press `enter`

#### Delete

- Press `r` to go the `refs` view
- Press `!` to delete branch
- Press `y` and `enter` to confirm

### Stash

#### Pop

- Press `y` to go to the `stash` view
- Press `P` to pop stash
- Press `enter`

#### Drop

- Press `y` to go to the `stash` view
- Press `!` to drop stash
- Press `y` and `enter` to confirm
