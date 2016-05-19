# Statistical Mechanics Theory and Molecular simulation written by Mark E. Tuckerman

Contributers: SM@ANYINT

Tips for new contributers:


You should know a little bit about what is Git and what is GitHub.
Use www.baidu.com if you feel that you are not clear enough about them.
<br>
<br>
1. Set up the project on your own computer:
--------------------------------------------

####1.1 Get your own GitHub account

####1.2 Download GitHub Desktop (https://desktop.github.com/) and install
        a brief introduction to it: (https://github.com/integrations/github-desktop)
        
        it will install a GitHub and a Git Shell
        GitHub is mainly used to visualize change history
        Git Shell is for version control and changes submit
####1.3 Accept invitation to the SM-at-ANYINT team
        you should offer me your GitHub account name for me to invite you
####1.4 Clone StatisticalMechanics to your Git Desktop 
    
        by clicking "Clone in Desktop" button at the lower right corner on page 
            https://github.com/SM-at-THU/StatisticalMechanics
        or by clicking "+" button at the upper left corner on GitHub Desktop, then
            choose "SM-at-THU"(it should appear if you accept the invitation successfully), "clone", "StatisticalMechanics" and finally "Clone repository"(at the bottom)
            
        in both way GitHub Desktop will ask you to browse a path for you to put the clone of StatisticalMechanics.
            default path(C:\Users\<your account>\Documents\GitHub) is suggested
            
  
<br>
<br>

2.Using GitHub desktop:
---------------------

####2.1 Use the tags to view current changes and change history

####2.2 When chosen the Changes tag, you can see your changes in the subwindow below. Type something in the Summary and Description and then you can commit your changes. 

####2.3 Click the Sync button at the upper right corner to sync your changes to online documents.

####2.4 When chosen the History tag, you can select any changes someone made before and see the detail changes in every files. You can also make inline comments by viewing the changes in the webpage.

3. Using Git Shell(Not necessary, GitHub desktop works well in both Windows and Mac OS)
------------------

    Although GitHub Desktop offers functions such as publish and synchronize, they are not clear enough. 
    Sometimes you modified your file and clicked "sync" in GitHub Desktop, but the file remains unchanged on the GitHub website. So we need Git Shell.
    
    Introduction to some Git commands:
    
        (http://blog.csdn.net/chun799/article/details/9095635)
        
    Only commands listed below are usually needed:
    
####3.1 Open Git Shell and browse to the directory of project StatisticalMechanics
        if you clone StatisticalMechanics in the suggested path, you only need to input "cd smtms"
        
####3.2 Use 
    
                git status
                
        to check modified files, files not change and files Git didn't track
        There are usually three kinds of file status:
            Changes to be committed: files whose changes will be uploaded
            Changes not staged for commit: files changed but won't be uploaded
            Untracked files: files which Git didn't track their changes
            
####3.3 Use 
    
                git add <foldername or filename>
                
        to add folders and files from "Untracked files" and "Changes not staged for commit"
            to "Changes to be committed"
        you can use "*" for abbreviate, e.g., git add class* will add all folders and files whose name begin with "class" 
            
####3.4 Use 
    
                git commit -m "<some notes here>"
                
        to commit changes of files which are in "Changes to be committed"
        Be aware that after this command the changes is still local
        
####3.5 Use
    
                git push
                
        to submit your local changes online
        things on (https://github.com/SMTMSbyMET/smtms) should change now

####3.6 Use
                git fetch
        
        to get changes from website to your local repository
        better to use git status to check changes first

        
<br>
<br>

4. Directions from Mr. Si Ha
-----------------------------

####4.1 我已经建立了两个文件夹, 分别是 Chapter 1 和 Chapter 2. 每个文件夹包含一个 .tex 文档, 一个 .pdf 文档和一个名为 figures 的文件夹

####4.2 想添加答案的同学, 先在自己的电脑上写好 TeX 文档, 然后复制到相应章节中的 .tex 文档中, 编译之后把 .tex 文档和 .pdf 同步上来

####4.3 如果需要插图的话, 在 figures 文件夹中建立你自己的一个子文件夹, 将你需要用到的图片放进去, 然后通过相对路径调用即可

####4.4 复制前先同步一次保证本地的文件是最新的，然后编译没问题了再commit你的change，然后再同步即可

很惭愧, 一点微小的工作

--last edit by ANYINT 2016-5-20
    
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />
