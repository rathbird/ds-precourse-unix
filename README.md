# CLI Sentence
Using only the `cd`, `ls` and `cp` commands (don't use finder or mkdir), copy folders from the verbs, adverbs, nouns and conjunction folders into the `sentence` directory to create a directory heirarchy that forms a sentence.

# Example
`sentence/the/zebra/joyously/dreamt/while/the/lion/secretively/leapt`

# Tips
* Use tab completion to help you narrow down what folders to copy

PS C:\Users\rathb\AppData\Local\Temp\GIT> git clone https://github.com/rathbird/ds-precourse-unix.git
Cloning into 'ds-precourse-unix'...
remote: Compressing objects: 100% (2/2), done.
remote: Total 38 (delta 0), reused 1 (delta 0), pack-reused 36
Receiving objects: 100% (38/38), 28.37 KiB | 453.00 KiB/s, done.
Resolving deltas: 100% (5/5), done.
PS C:\Users\rathb\AppData\Local\Temp\GIT> cd ds-precourse-unix
PS C:\Users\rathb\AppData\Local\Temp\GIT\ds-precourse-unix> ls


Mode                 LastWriteTime         Length Name                                                                                                                                                                                       
----                 -------------         ------ ----                                                                                                                                                                                       
d-----         5/11/2021   8:29 AM                adverbs                                                                                                                                                                                    
d-----         5/11/2021   8:29 AM                conjunctions                                                                                                                                                                               
d-----         5/11/2021   8:29 AM                example                                                                                                                                                                                    
d-----         5/11/2021   8:29 AM                nouns                                                                                                                                                                                      
d-----         5/11/2021   8:30 AM                sentence                                                                                                                                                                                   
d-----         5/11/2021   8:29 AM                the
d-----         5/11/2021   8:29 AM                verbs
PS C:\Users\rathb\AppData\Local\Temp\GIT\ds-precourse-unix> git commit -m "unix commit robin stewart"
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean
PS C:\Users\rathb\AppData\Local\Temp\GIT\ds-precourse-unix> git push -u origin master
Everything up-to-date
Branch 'master' set up to track remote branch 'master' from 'origin'.
PS C:\Users\rathb\AppData\Local\Temp\GIT\ds-precourse-unix> cd sentence
PS C:\Users\rathb\AppData\Local\Temp\GIT\ds-precourse-unix\sentence> cp \Users\rathb\OneDrive\Documents\ds-precourse-unix\sentence\the


    Directory: C:\Users\rathb\AppData\Local\Temp\GIT\ds-precourse-unix\sentence


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----

PS C:\Users\rathb\AppData\Local\Temp\GIT\ds-precourse-unix\sentence> cd the
PS C:\Users\rathb\AppData\Local\Temp\GIT\ds-precourse-unix\sentence\the> ls
PS C:\Users\rathb\AppData\Local\Temp\GIT\ds-precourse-unix\sentence\the> cd ..\
PS C:\Users\rathb\AppData\Local\Temp\GIT\ds-precourse-unix\sentence> rm the
PS C:\Users\rathb\AppData\Local\Temp\GIT\ds-precourse-unix\sentence> ls


    Directory: C:\Users\rathb\AppData\Local\Temp\GIT\ds-precourse-unix\sentence




PS C:\Users\rathb\AppData\Local\Temp\GIT\ds-precourse-unix\sentence> cd -r \Users\rathb\OneDrive\Documents\ds-precourse-unix\sentence\the
Set-Location : A parameter cannot be found that matches parameter name 'r'.
At line:1 char:4
+ cd -r \Users\rathb\OneDrive\Documents\ds-precourse-unix\sentence\the
+    ~~
    + CategoryInfo          : InvalidArgument: (:) [Set-Location], ParameterBindingException
    + FullyQualifiedErrorId : NamedParameterNotFound,Microsoft.PowerShell.Commands.SetLocationCommand

PS C:\Users\rathb\AppData\Local\Temp\GIT\ds-precourse-unix\sentence> cp -r \Users\rathb\OneDrive\Documents\ds-precourse-unix\sentence\the
PS C:\Users\rathb\AppData\Local\Temp\GIT\ds-precourse-unix\sentence> git add .
PS C:\Users\rathb\AppData\Local\Temp\GIT\ds-precourse-unix\sentence> ls


    Directory: C:\Users\rathb\AppData\Local\Temp\GIT\ds-precourse-unix\sentence


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         5/11/2021   8:40 AM                the
-a----         5/11/2021   8:29 AM              0 .gitkeep


PS C:\Users\rathb\AppData\Local\Temp\GIT\ds-precourse-unix\sentence> cd ..\
PS C:\Users\rathb\AppData\Local\Temp\GIT\ds-precourse-unix> git add .
PS C:\Users\rathb\AppData\Local\Temp\GIT\ds-precourse-unix> cd .\sentence\the\aardvark\abnormally\arose\after\the\accountant\accidentally\burned\
PS C:\Users\rathb\AppData\Local\Temp\GIT\ds-precourse-unix\sentence\the\aardvark\abnormally\arose\after\the\accountant\accidentally\burned>