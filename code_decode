import string
import random   
coding=input("what do you want to do 1 for code & 0 for decode ")
str=input("enter your message: ")
words=str.split()    
coding = True if (coding=='1') else False
if(coding):
    nwords=[]
    r1='str'
    r2='fhj'
    for word in words:
     if(len(word)>=3):
        strn=r1+word[1:]+word[0]+r2
        nwords.append(strn)
        print(nwords)
    else:
        nwords.append(word[::-1])
else:
    nwords=[]
    for word in words:
     if(len(word)>=3):
        strn=word[-4]+word[3:-4]
        nwords.append(strn)
        print(nwords)
    else:
        nwords.append(word[::-1])

