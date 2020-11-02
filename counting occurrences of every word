str=input()
str=str+" "
wrd=""
lst=[]
#this list stores the word the first time it occurs
extra=[]
for i in str:
    if i==" ":
        lst.append(wrd)
        wrd=""
    else:
        wrd=wrd+i
for i in lst:
    #if the word hasn't been encountered earlier
    #this condition is evaluated
    if i not in extra:
        n=lst.count(i)
        print(i,"exists",n,"times")
        extra.append(i)
