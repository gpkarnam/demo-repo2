# Demo 2
created in file system and published as repo

1. convert this folder into a git
    git init 
    git add .
    git commit -m "adsfa"
2. git push origin main
    This does not work as remote origin DNE
    goto to github.com and create a new repo with name same as folder
    copy the ssh key entry
    git@github.com:gpkarnam/demo-repo2.git
3. add this repo to local git folder
   git remote add origin git@github.com:gpkarnam/demo-repo2.git
   git push -u origin main
   
$    git remote add origin git@github.com:gpkarnam/demo-repo2.git

skgur@LAPTOP-634LMU0N MINGW64 ~/Downloads/gp/Code/demo-repo2 (main)
$ git push origin main
The authenticity of host 'github.com (13.234.176.102)' can't be established.    
RSA key fingerprint is SHA256:nThbg6kXUpJWGl7E1IGOCspRomTxdCARLviKw6E5SY8.      
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes        
Warning: Permanently added 'github.com' (RSA) to the list of known hosts.       
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 299 bytes | 29.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:gpkarnam/demo-repo2.git
 * [new branch]      main -> main

DEFAULT
set remote origin and main as defaults,
git push -u origin main
next time onwards you can use git push
=============
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main
=========================================
