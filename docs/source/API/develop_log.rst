Development Log
===============

Brain and terminal dumps.

Thursday, March 18, 2021 06:40:42 PM
------------------------------------

Created use cases. Initialized git repository on github.

.. code:: console

   (today) [18:38:18 today]$ ls
   docs  main.py
   (today) [18:38:19 today]$ git init
   Initialized empty Git repository in /home/kendall/Projects/pythonprojects/today/.git/
   (today) [18:38:22 today]$ git add .
   (today) [18:38:27 today]$ git status
   On branch master

   No commits yet
   ...
   (today) [18:38:30 today]$ git commit -m "Added initial desired use cases."
   [master (root-commit) 6abc5bd] Added initial desired use cases.
   40 files changed, 15512 insertions(+)
   ...
   (today) [18:39:04 today]$ git remote add origin git@github.com:kjnoraas/today.git
   (today) [18:39:22 today]$ git push origin master
   Warning: Permanently added the RSA host key for IP address '140.82.112.3' to the list of known hosts.
   Enter passphrase for key '/home/kendall/.ssh/id_ed25519': 
   Enumerating objects: 51, done.
   Counting objects: 100% (51/51), done.
   Delta compression using up to 8 threads
   Compressing objects: 100% (48/48), done.
   Writing objects: 100% (51/51), 163.16 KiB | 1.43 MiB/s, done.
   Total 51 (delta 5), reused 0 (delta 0), pack-reused 0
   remote: Resolving deltas: 100% (5/5), done.
   To github.com:kjnoraas/today.git
   * [new branch]      master -> master

