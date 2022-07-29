# git-flow
git-flow Job
1.	所有步骤按上诉流程来，其中红色x的是有冲突记录的。，
2.	在本地：创建本地仓库以及各个分支，提交到指定github：（脑挫了，把feature也提交了）
  
  
  
3.	从github上拉取下来。
4.	修改hotfix，合并到master，提交github，得到masterv0.2版本。（发生一次冲突：把hotfix的one 文件内部修改，然后把master文件内部修改，然后发生冲突，冲突如下：）
 
   
最后还是改成 ：
 
提交，保存目录。即可。
5.	从develop创建feature1，修改内部的dvelop文件，并形成d0=>d1=>d2=>d3=>d4，不合并，不提交到github。
6.	修改develop的develop文件从d0=>d1=>d2版本,并从d2版本创建分支feature2。
7.	Feature2把d2=>修改到d4版本；
8.	Develop把d2=>修改到d3版本，并把hotfix合并到develop。
9.	把feature2合并到develop版本。发生了冲突如下：
 
最后改成了develop内部为feature2的d4版本。
10.	把develop合并到release中，并修改release文件到从r0=>r1=r2版本。
11.	并把release分支合并到master中。形成masterV1.0本版。
12.	最后把release合并到develop中。
13.	全部提交github。
