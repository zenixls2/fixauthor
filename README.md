# Git author modification script

## Usage
* copy the git-author-rewrite.sh to project git folder.
* Replace the `OLD_NAME`, `CORRECT_NAME`, and `CORRECT_EMAIL`
* And execute `git-author-rewrite.sh` in folder.
* Then execute the following command:
```bash
git push --force --tags origin 'refs/heads/*'
```
