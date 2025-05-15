# one-to-one-ines
C:\Users\elitebook> C:\Users\elitebook>mkdir learn_git

C:\Users\elitebook>cd learn_git

C:\Users\elitebook\learn_git>echo "">third.txt

C:\Users\elitebook\learn_git>git boolean ini:/Users/elitebook/learn_git/.git/Initialized empty Git repository

C:\Users\elitebook\learn_git>git add third.txt

C:\Users\elitebook\learn_git git commit -m"adding third.txt" [master ) b95f5a4] adding third.txt 1 file changed, 1 insertion (+) create mode 100644 third.txt

C:\Users\elitebook\learn_git>git log

commit b95f5a4cfc76603238888ef5c49822dacc28b75e (HEAD -> master) Author: noussa25 <chetibiines5@gmail.com> Date: Thu May 15 20:30:13 2025 +0100

adding third.txt

C:\Users\elitebook\learn_git>echo "">fourth.txt

C:\Users\elitebook\learn_git>gut add fourth.txt 'gut' n'est pas reconnu en tant que commande interne ou externe, un programme exécutable ou un fichier de commandes.

C:\Users\elitebook\learn_git>git add fourth.txt

C:\Users\elitebook\learn_git git commit -m"adding fourth.txt" [master d675886] adding fourth. 1 file changed, 1 insertion (+) create mode 100644 fourth fourth.txt

C:\Users\elitebook\learn_git>rm third.txt 'rm' n'est pas reconnu en tant que commande interne ou externe, un programme exécutable ou un fichier de commandes.

C:\Users\elitebook\learn_git git rm third.txt rm 'third.txt'

C:\Users\elitebook\learn_git git commit -m"removing third.txt"
C:\Users\elitebook learn_git git commit -m"adding third.txt"

[master (root-commit) b95f5a4] adding third.txt

1 file changed, 1 insertion (+)

create mode 100644 third.txt

C:\Users\elitebook\learn_git>git log

commit b95f5a4cfc76603238888ef5c49822dacc28b75e (HEAD -> master)

Author: noussa25 <chetibiines5@gmail.com>

Date: Thu May 15 20:30:13 2025 +0100

adding third.txt

C:\Users\elitebook\learn_git>echo "">fourth.txt

C:\Users\elitebook\learn_git>git add fourth.txt

C:\Users\elitebook\learn_git git commit -m"adding fourth.txt"

[master d675886] adding fourth.txt

1 file changed, 1 insertion (+)

create mode 100644 fourth.txt

C:\Users\elitebook\learn_git>rm third.txt

'rm' n'est pas reconnu en tant que commande interne ou externe, un programme exécutable ou un fichier de commandes.

C:\Users\elitebook\learn_git>git rm third.txt rm 'third.txt'
C:\Users\elitebook\learn_git>git add.

git: 'add.' is not a git command. See 'git --help'.

The most similar command is add

C:\Users\elitebook\learn_git git commit -m"removing third.txt"

On branch master

nothing to commit, working tree clean

C:\Users\elitebook\learn_git>git log

commit a0660da3c3beb7735e97e9af0f0402b0f12e26b8 (HEAD master)

Author: noussa25 <chetibiines5@gmail.com>

Date: Thu May 15 20:41:23 2025 +0100

removing third.txt

commit d675886a948602e70504f7f0eb0237f410674046

Author: noussa25 <chetibiines5@gmail.com>

Date: Thu May 15 20:39:34 2025 +0100

adding fourth.txt

commit b95f5a4cfc76603238888ef5c49822dacc28b75e

Author: noussa25 <chetibiines5@gmail.com>

Date: Thu May 15 20:30:13 2025 +0100

adding third.txt

C:\Users\elitebook\learn_git>git config --global core.pager=cat

error: invalid key: core.pager=cat

C:\Users\elitebook\learn_git>git config --global --list

filter.lfs.clean=git-lfs clean --%f

filter.lfs.smudge=git-lfs smudge -- %f --

filter.lfs.process=git-lfs filter-process

filter.lfs.required=true

user.name=noussa25

user.email=chetibiines5@gmail.com
