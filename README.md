Todas as modificações foram feitas na ramificaçeos modificacoes
 1 -  Ordenamento dos dígitos da calculadora
 2 -  Correção da tecla DEL
 3 -  Inclusão a função portagens
 4 -  Mudanças de cores
 
 
 conteudo do git commit local.
 
 janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (master)
$ git checkout -b modificacoes
 
 janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (modificacoes)
$ git branch
  master
* modificacoes

janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (modificacoes)
$ git add App.js

janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (modificacoes)
$ git add README.md

janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (modificacoes)
$ git commit -m "Alteração da ordem dos número do teclado da calculadora"
On branch modificacoes
Your branch is ahead of 'origin/modificacoes' by 3 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (modificacoes)
$ git add App.js

janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (modificacoes)
$ git commit -m "Criação da funcão inversão de valores"                         On branch modificacoes
Your branch is ahead of 'origin/modificacoes' by 3 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   App.js

no changes added to commit (use "git add" and/or "git commit -a")

janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (modificacoes)
$ git add App.js

janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (modificacoes)
$ git commit -m "Alteração da ordem dos número do teclado da calculadora"
[modificacoes 08a1118] Alteração da ordem dos número do teclado da calculadora
 1 file changed, 1 insertion(+), 1 deletion(-)

janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (modificacoes)
$ git add App.js

janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (modificacoes)
$ git commit -m "Criação da função de porcentagens"                             On branch modificacoes
Your branch is ahead of 'origin/modificacoes' by 4 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (modificacoes)
$ git commit -m "Criação da função de porcentagens"
On branch modificacoes
Your branch is ahead of 'origin/modificacoes' by 4 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (modificacoes)
$ git commit -m "Criação da função de porcentagens"
On branch modificacoes
Your branch is ahead of 'origin/modificacoes' by 4 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (modificacoes)
$ git add App.js

janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (modificacoes)
$ git commit -m "Mudança das cores da calculadora"                              On branch modificacoes
Your branch is ahead of 'origin/modificacoes' by 4 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (modificacoes)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (master)
$ git merge modificacoes
Auto-merging App.js
hint: Waiting for your editor to close the file...
Merge made by the 'recursive' strategy.
 App.js | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)

janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (master)
$ git branch -M master

janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (master)
$ git remote add origin https://github.com/janunesde/Atividade_2_uc13.git
error: remote origin already exists.

janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (master)
$ git push -u origin master
Enumerating objects: 11, done.
Counting objects: 100% (11/11), done.
Delta compression using up to 2 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 745 bytes | 745.00 KiB/s, done.
Total 5 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 2 local objects.
To https://github.com/janunesde/Atividade_2_uc13.git
   d5764ba..4967a0e  master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (master)
$ git checkout modificacoes
Switched to branch 'modificacoes'
Your branch is ahead of 'origin/modificacoes' by 4 commits.
  (use "git push" to publish your local commits)

janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (modificacoes)
$ git branch -M modificacoes

janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (modificacoes)
$ git push -u origin modificacoes
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/janunesde/Atividade_2_uc13.git
   965ffda..08a1118  modificacoes -> modificacoes
Branch 'modificacoes' set up to track remote branch 'modificacoes' from 'origin'.

janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (modificacoes)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

janun@DESKTOP-AI472O7 MINGW64 ~/senac_mobile/UC13/Atividade2 (master)
$ git log --graph --all
*   commit 4967a0ecfd95ae79d5234e4bee93830f9f07186d (HEAD -> master, origin/master)
|\  Merge: d5764ba 08a1118
| | Author: José Antônio Nunes de Morais <janunesde@gmail.com>
| | Date:   Mon Oct 4 14:07:28 2021 -0300
| |
| |     Merge branch 'modificacoes'
| |
| * commit 08a11183dc6c636f7d6804bd11a4540e0e52a367 (origin/modificacoes, modificacoes)
| | Author: José Antônio Nunes de Morais <janunesde@gmail.com>
| | Date:   Mon Oct 4 14:03:54 2021 -0300
| |
| |     Alteração da ordem dos número do teclado da calculadora
| |
| *   commit facc43f97fe1d610ebcbaf995118e96b143fc61f
| |\  Merge: 4999def 965ffda
:...skipping...
*   commit 4967a0ecfd95ae79d5234e4bee93830f9f07186d (HEAD -> master, origin/master)
|\  Merge: d5764ba 08a1118
| | Author: José Antônio Nunes de Morais <janunesde@gmail.com>
| | Date:   Mon Oct 4 14:07:28 2021 -0300
| |
| |     Merge branch 'modificacoes'
| |
| * commit 08a11183dc6c636f7d6804bd11a4540e0e52a367 (origin/modificacoes, modificacoes)
| | Author: José Antônio Nunes de Morais <janunesde@gmail.com>
| | Date:   Mon Oct 4 14:03:54 2021 -0300
| |
| |     Alteração da ordem dos número do teclado da calculadora
| |
| *   commit facc43f97fe1d610ebcbaf995118e96b143fc61f
| |\  Merge: 4999def 965ffda
| | | Author: José Antônio Nunes de Morais <janunesde@gmail.com>
| | | Date:   Mon Oct 4 14:00:54 2021 -0300
| | |
| | |     Merge branch 'modificacoes' of https://github.com/janunesde/Atividade_2_uc13 into modificacoes
| | |
| | * commit 965ffda21f4237b37956140b841a6e413254ae44
| | | Author: José Antônio Nunes de Morias <78913415+janunesde@users.noreply.github.com>
| | | Date:   Mon Oct 4 10:32:47 2021 -0300
| | |
| | |     Update App.js
| | |
* | | commit d5764ba52dc89a8dc14e4e5cef1900891b818951
:...skipping...
*   commit 4967a0ecfd95ae79d5234e4bee93830f9f07186d (HEAD -> master, origin/master)
|\  Merge: d5764ba 08a1118
| | Author: José Antônio Nunes de Morais <janunesde@gmail.com>
| | Date:   Mon Oct 4 14:07:28 2021 -0300
| |
| |     Merge branch 'modificacoes'
| |
| * commit 08a11183dc6c636f7d6804bd11a4540e0e52a367 (origin/modificacoes, modificacoes)
| | Author: José Antônio Nunes de Morais <janunesde@gmail.com>
| | Date:   Mon Oct 4 14:03:54 2021 -0300
| |
| |     Alteração da ordem dos número do teclado da calculadora
| |
| *   commit facc43f97fe1d610ebcbaf995118e96b143fc61f
| |\  Merge: 4999def 965ffda
| | | Author: José Antônio Nunes de Morais <janunesde@gmail.com>
| | | Date:   Mon Oct 4 14:00:54 2021 -0300
| | |
| | |     Merge branch 'modificacoes' of https://github.com/janunesde/Atividade_2_uc13 into modificacoes
| | |
| | * commit 965ffda21f4237b37956140b841a6e413254ae44
| | | Author: José Antônio Nunes de Morias <78913415+janunesde@users.noreply.github.com>
| | | Date:   Mon Oct 4 10:32:47 2021 -0300
| | |
| | |     Update App.js
| | |
* | | commit d5764ba52dc89a8dc14e4e5cef1900891b818951
|\| | Merge: e2f5d7b 4999def
| | | Author: José Antônio Nunes de Morais <janunesde@gmail.com>
| | | Date:   Mon Oct 4 13:51:37 2021 -0300
| | |
| | |     Merge branch 'modificacoes'
| | |
| * | commit 4999def6a74b93a61b4b99637e8a91c1ef6aa841
| | | Author: José Antônio Nunes de Morais <janunesde@gmail.com>
| | | Date:   Mon Oct 4 13:46:52 2021 -0300
| | |
| | |     Alteração da ordem dos número do teclado da calculadora
| | |
| * | commit 487ef39baf8b3cfd53c52d72a96a4f3da97f1b14
| |/  Author: José Antônio Nunes de Morais <janunesde@gmail.com>
| |   Date:   Mon Oct 4 13:44:58 2021 -0300
| |
| |       Alteração da ordem dos número do teclado da calculadora
| |
* | commit e2f5d7b3236e749650416333da3c2b2a1e73979c
|/  Author: José Antônio Nunes de Morias <78913415+janunesde@users.noreply.github.com>
|   Date:   Mon Oct 4 10:31:29 2021 -0300
|
|       Update App.js
|
* commit 1dea0aa672b05421f6223f1dca64a39411935ad7
| Author: José Antônio Nunes de Morais <janunesde@gmail.com>
| Date:   Mon Oct 4 13:16:06 2021 -0300
|
|     Mudanção testadas e aprovadas
|
* commit f633caadd8c162c89e82bbe51e725947c35b01bf
:
