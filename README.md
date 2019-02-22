# tigconfig

The config I use for [tig](https://github.com/jonas/tig)

## Cheat sheet

Command | Description
-- | --
**D** | Delete unstaged file
**C** | Commit all staged files
**1** | Stage one line
**u** | Stage file or stage one chunk 
**+** | Amend to previous commit
**P** | Push
**I** | Put file in gitignore
**B** | Open commit on github.com

## Use cases

### Branches

#### Checkout

- Press `r` to go the `refs` view
- Press `C` to checkout branch
- Press `y` and `enter` to confirm

#### Delete

- Press `r` to go the `refs` view
- Press `!` to delete branch
- Press `y` and `enter` to confirm

### Stash

#### Pop

- Press `y` to go to the `stash` view
- Press `P` to pop stash
- Press `y` and `enter` to confirm

#### Drop
- Press `y` to go to the `stash` view
- Press `!` to drop stash
- Press `y` and `enter` to confirm
