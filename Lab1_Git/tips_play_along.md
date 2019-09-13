# Tips

## Pushing to a Different Remote After a Clone
1. Create a new directory on your system
2. Move into the directory
3. `git clone https://github.com/cedric-c/seg2505_2017`. This will create a repo of `seg2505_2017` inside your current folder
4. Move into this folder
5. `git remote -v` to check where you will push to, you may not always have permission to push to these locations
6. `git remote add upstream https://github.com/cedric-c/branche_b/` to add this repo as a list of available repos
7. `git remote set-url origin https://github.com/cedric-c/branche_b/` to change where pushes are sent to

## Erreur typiques

Vous avez essayé un `git push origin master` et vous recevez ceci

    ! [rejected]        master -> master (fetch first)
    error: failed to push some refs to 'https://github.com/cedric-c/branche_b/'
    hint: Updates were rejected because the remote contains work that you do
    hint: not have locally. This is usually caused by another repository pushing
    hint: to the same ref. You may want to first integrate the remote changes
    hint: (e.g., 'git pull ...') before pushing again.
    hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Problème : Vous n'avez pas la version la plus courrantes de la branch master.
Résolution : Faites un `git pull origin master` et ensuite votre `git push origin master` pour envoyez les changements à la nouvelle branche.