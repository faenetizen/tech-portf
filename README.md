# Just whatever | I'm just starting out

#Machine Config:
* **OS:** Windows 11 Home
* **Environment:** Git Bash (MINGW64)
* **Connection Type:** SSH (Ed25519 Key)

---

#Useful Command Sheet

#git deployment loop
Everytime a file is modified, run this sequence to push changes to your online repository.

\'\'\'bash
git add .
git commit -m "my comment"
git push
\'\'\'

#useful diagnostic commands 
Useful for checking network handshake integrity:

* 'ssh -T git@github.com' - verifies github secure auth
* 'git remote -v' - displays configured tracking urls 
