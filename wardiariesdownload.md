    1  mkdir wget-activehistory
    2  cd wget-activehistory
    3  wget http://activehistory.ca/papers/
    4  wget -r --no-parent -w 2 --limit-rate=20k http://activehistory.ca/papers/
    5  history > wgetdownload.md
    6  ls
    7  mkdir war-diary
    8  cd war-diary
    9  pwd
   10  cd ~
   
   11  mkdir war-diary
   
   12  cd war-diary
   
   13  pwd
   
   14  nano urls.py
   
   15  python urls.py
   
   16  ls
   
   17  nano urls.txt
   
   18  wget -i urls.txt -r --no-parent -nd -w 2 --limit-rate=100k
   
   19  ls
   
   20  history > wardiariesdownload.md

Commands 1-6 are from the previous part of exercise 2 (and were recorded in wgetdownload.md).
