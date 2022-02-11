# grade-sno=int(input('enter student number'))
sname=input('enter student name')
sgroup=input('enter student group')
s1=int(input('enter maths marks'))
s2=int(input('enter physics marks'))
s3=int(input('enter computer  marks'))
s4=int(input('enter telugu marks'))
s5=int(input('enter english marks'))
s6=int(input('enter OB marks'))  
total=s1+s2+s3+s4+s5+s6
avg=(s1+s2+s3+s4+s5+s6)/2
if((s1>=35)&(s2>=35)&(s3>=35)&(s4>=35)&(s5>=35)&(s6>=35)):
    print ('fail')
else:
    print('pass')
if(avg>=91):
    print (O grade')
elif(avg>=81):
     print('A grade')
elif(avg>=71):
     print ('B grade')  
elif(avg>=61):
     print ('C grade')
elif(avg>=51):
     print ('D grade')
elif(avg>=41):
     print('pass')
else:
     print ('fail')
