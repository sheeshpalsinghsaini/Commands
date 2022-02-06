# Commands

<<<<<<< HEAD

# ====================================================== Basic of Git ==========================================================

            Git is a type of version control system. Saving the history of project.
                track which person, in which project and where make changes.
                ->Save all changes of all records.

            Note: history are stored in .git folder[repo] in local system.
            GitHub: platfrom, online website that allow us to host our repository[folder].










            set UserName & E-mail:
                git config --global user.name "sheeshpalsinghsaini"                     //set a userName.
                git config --global user.email "123sheeshpalsinghsaini@gmail.com"       //set email.

                git status                                   //show current status
                git init                                     //initialize git repo.[make .git hidden folder]


            Note:
            -> Untracked files          //git have no control of these file
            -> track files              //git have all information about these files.
            -> commits                   //ready to push for remote repository.
            -> modify                    //some changes in a file after it need to add and commit again.

                git add file1Name file2Name ....        //track by git now.
                git add .                               //track all file by git[untrack files].

                
                git commit -m "provide a messages"      //commit git tracked files. now we can push these file on remote.
                git remote add origin //provide https://address         //link remote in current folder. and give origin name.
                git config --get remote.origin.url                      //print origin path.
                git remote                                              //print which name give to remote location
                git remote -v                                           //print fetch and push path of remote location.

                git push -u origin              //push content to origin in default branch
                git push -u origin master       //push into origin master branch.

                










                Working_Dir ---[git add.]-->    StagginArea/CacheArea   --[gitCommit]->     LocalRepo/CommitedArea  --[gitPush]--->     RemoteRepo
                    |                                   |                                                |        <----------------------gitPull
                    |                                   |                                                |                                  |






                git log                                                 //show all previous commits with all details



  ###  git generate hashcode for every commits:

                git log --oneline                   //show all commits in short

                we can create branch from every commits[hashcode].
                git log -1                          //show last one commit
                git log -2                          //show last two commit
                git log --grep="give msg"           //filter according to msg.
                    like: git log --grep="only"     //filter out in which commit is only apear.
                
                git log --since="30/01/2022"        //show all commits after give date.
                git log --until="01/02/2022"        //show all commits till give date.

=======
>>>>>>> b14927c9d39ce62ee8a08226d171c9a206df0c63
