# Get Repo Downloader



This module is used to batch git clone the large file system 

needed lib:

git-lfs: https://askubuntu.com/questions/799341/how-to-install-git-lfs-on-ubuntu-16-04

GitPython : https://gitpython.readthedocs.io/en/stable/tutorial.html

Run under back ground:

```
sudo nohup python3 gitDownloader.py &
```

Check the process or stop:

```
sud ps ax | grep python3
```

Check folder size:

```
du -sh /mnt/storage/llmModules/Vicuna-7B/
```

