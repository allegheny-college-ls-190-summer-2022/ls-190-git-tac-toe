# LS 190: Git branching git-tac-toe

**Important**: Follow long with the instruction happening on the Google Meet. If you'd like to play with friends later, copy and paste the table (removing all moves) to play.

## Rules

* In order of turns, `pull` from the `main` branch
* Then, make a branch with your username:
```
git checkout -b USERNAME
```
* Make your move on the board by filling in a square in the table below with either an `X` or an `O`
  * If an `X` has just been entered, you're an `O`, if an `O` is the latest move made, enter an `X`
* `git add -A`; `git commit -m "MESSAGE"`; and `git push origin BRANCH_NAME` to submit your move
* Head to the GitHub repository for this game, linked below:
  * 
* Make a `Pull Request` and add the instructor as a reviewer ot submit your move

## Game board

### Game 1

|GIT|TAC|TOE|
|---|---|---|
| X | X  | X | 
|   | O |   |
|  O |   |   |

### Game 2

|GIT|TAC|TOE|
|---|---|---|
|   |   |   | 
|   |   |   |
|   |   |   |