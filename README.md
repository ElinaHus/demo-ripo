# Brief Description of video guide on github

GitHub has many shortcuts for text in .md file
readme is a default file that presents in every github project

## some commands

* to bring the github repository to my comp on terminal on visual :

    git clone https://github.com/ElinaHus/demo-ripo.git

    
* to see the changes that made on local repository that are not saved to github:

    git status

    if a new file created in local repository, then after git status it will be shown as 'Untracked files'
    so u need to tell git to track them too. For that, use :

        git add .   # track all of the files used in folder
        git index.html  # track index.html file

* to commit changes:

    git commit -m  "added new html file" -m  "some description"    # -m stands for a message and it must be included, while second -m is for description and its optional

* if changes made on my local repository in visual, then it can be transfered to github by following steps:
    * first create a ssh key by ssh-keygen -t rsa -b 4096 -C "elina.huseynova2003@gmail.com"
    * then, name it ( in this repository i named it testkey)
    * password can be skipped
    * two testkeys generated: testkey (private) and testkey.pun (publib)
    * cat testkey.pub to access the content of testkey.pub, and copy the key and paste in settings in github add key section

* for pushing into the remote repository

    git init 
    git push -u origin main 

    if donesn't work, then u should track files:

    git add . 
    git commit -m "..."

    hint: origin is the name of the remote repository. to see the names of remote repositories type:

    git remote -v

* for donwloading updates from the remote to local repository

    git fetch origin

###







    

    
