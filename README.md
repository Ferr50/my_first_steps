# my_first_steps
praticando git

Questão 1:
https://github.com/Ferr50/my_first_steps.git


Questão 2:
Last login: Mon Sep 27 17:56:15 on ttys000
fernando in ~ 
❯ cd Desktop 
fernando in ~/Desktop 
❯ cd AlphaED 
fernando in ~/Desktop/AlphaED 
❯ cd Git01  
fernando in Desktop/AlphaED/Git01 
❯ git init               
Initialized empty Git repository in /Users/fernando/Desktop/AlphaED/Git01/.git/
fernando in Git01 on  master 
❯ git pull https://github.com/Ferr50/my_first_steps.git
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (4/4), done.
From https://github.com/Ferr50/my_first_steps
 * branch            HEAD       -> FETCH_HEAD


 Questão 3:
 fernando in Git01 on  master 
❯ git branch -M "main"                                              
fernando in Git01 on  main 
❯ touch ola_mundo.txt
fernando in Git01 on  main [?] 
❯ git add ola_mundo.txt
fernando in Git01 on  main [+] 
❯ git commit -m "meu primeiro commit"                   
[main ace435e] meu primeiro commit
 1 file changed, 1 insertion(+)
 create mode 100644 ola_mundo.txt
fernando in Git01 on  main 
❯ git push -u origin main                              
Counting objects: 3, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 352 bytes | 352.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/Ferr50/my_first_steps.git
   75c94da..ace435e  main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
fernando in Git01 on  main 
❯ 


Questão 4:
echo serei_ignorado.txt >> .gitignore