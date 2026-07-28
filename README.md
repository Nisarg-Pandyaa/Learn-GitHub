# Learn-GitHub
Repo for Learning GitHub. </br> </br>


- To Check If Git Is Installed Or Not : It will show the git version if present
```
git --version
```
</br> </br>

- To Setup Your GitHub With Name & Email :
```
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
</br> </br>

- To see your current Git configuration :
```
git config --global user.name
git config --global user.email
```
</br> </br>

- To Initialize Git Repository : `"Yo.. Git, Track My Code Folder"`
```
git init
```
</br> </br>

- To Stage a file in the current directory for commit : `"Folder Se GitHub K Staging Area Me Add Kardo"`
```
git add [file1 name] [file2 name] ...
```
</br> </br>

- To Stage ALL files in the current directory for commit : </br>
`Jo Bhi STAGING AREA Me Files Hoti Hea Usse Ab GIT Track Kar Sakta Hea`
```
git add .
```
</br> </br>

- To see Which files are in staging area (ready to commit) - in GREEN, Which files are modified but not staged - in RED & Which files are untracked (new files Git doesn't know about) :
```
git status
```
</br> </br>

- To snapshot files in staging area : `"It's Like A Checkpoint and I can comeback here anytime again"`
```
git commit -m "Any Commit Message..."
```
</br> </br>

- To See All the checkpoints:
```
git log
```
</br> </br>

- To See All the checkpoints in one line (but DATE & TIME & AUTHOR will not appear) :
```
git log --oneline
```
</br> </br>

- To get file back from staging area to local folder :
```
git restore --staged [file1 name] [file2 name] ...
```
</br> </br>
