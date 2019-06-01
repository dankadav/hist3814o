    1  ls
    2  sed -r -i.bak 's/(,)( [[0-9]{4})(.+)/\2/g' index.txt
    3  nano index.txt
    4  pwd
    5  sed -r -i.bak 's/~//g' index.txt
    6  nano index.txt
    7  sed -r -i.bak 's/(\b to \b)/,/g' index.txt
    8  nano index.txt
    9  sed -r -i.bak 's/,/(, )/g' index.txt
   10  nano index.txt
   
   11  sed -r -i.bak 's/(, )/, /g' index.txt
   
   12  nano index.txt
   
   13  sed -r -i.bak 's/(, )/,/g' index.txt
   
   14  nano index.txt
   
   15  sed -r -i.bak 's/((,))/,/g' index.txt
   
   16  nano index.txt
   
   17  sed -r -i.bak 's/(()(,)())/\2/g' index.txt
   
   18  nano index.txt
   
   19  ls
   
   20  nano index.txt.bak
   
   21  sed -r -i.bak 's/(\b () \b)/,/g' index.txt
   
   22  nano index.txt
   
   23  nano index.txt.bak
   
   24  nano index.txt
   
   25  sed -r -i.bak 's/[()]/,/g' index.txt
   
   26  nano index.txt
   
   27  sed -r -i.bak 's/,,/,/g' index.txt
   
   28  nano index.txt
   
   29  grep -r ".+,.+,.+," index.txt
   
   30  cp index.txt cleaned-correspondence.csv
   
   31  history > Module3-Commands.md
