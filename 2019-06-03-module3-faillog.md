# Module 3 Fail Log

## Exercise 1

```clear``` or ctrl+l to clear DHBox when it freezes

### Trial and Error

I thought I needed to have a space after the commas I added with the ```sed -r -i.bak 's/(\b to \b)/,/g' index.txt``` command so I tried to figure it out myself and add it.

1. sed -r -i.bak 's/,/(, )/g' index.txt - this replaced the commas  with (, )
2. sed -r -i.bak 's/(, )/, /g' index.txt - this didn't change anything
3. sed -r -i.bak 's/(, )/,/g' index.txt - this replaced the (, ) with (,)
4. sed -r -i.bak 's/((,))/,/g' index.txt - this tried to remove the brackets, but did nothing
5. sed -r -i.bak 's/(()(,)())/\2/g' index.txt - this removed the comma and left ()
6. sed -r -i.bak 's/(\b () \b)/,/g' index.txt - this did nothing
7. sed -r -i.bak 's/[()]/,/g' index.txt - this removed the brackets but left me with ,, instead of just one comma
8. sed -r -i.bak 's/,,/,/g' index.txt - this brought back the single commas (still no space though, but decided to leave it)

I used this [website](https://unix.stackexchange.com/questions/345154/replace-matching-parentheses-with-enclosing-content) to figure out how to write a command that would identify brackets as actual brackets (command 7 above), and replace them with commas

A SPACE AFTER A COMMA DOES NOT MATTER, remember for the future!

Everything else went well

## Exercise 2

Java JRE doesn't want to work with a Mac for some reason - it is not supported by newer versions of most browsers

```java -version``` can give more info if typed into terminal, terminal is the utilities folder in applications.

ctrl can be held down to bypass apple's nanny features
