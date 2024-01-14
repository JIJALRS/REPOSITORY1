# REPOSITORY1
word=input("ENTER A WORD in small letter ")
x=['a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z']
for i in range(0,26):  #ivide x intey index 0 to 25 aanu but number of elements 26 aanu
  if x[i] in word:
    print(x[i], word.count(x[i]))
