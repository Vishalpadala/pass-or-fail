# pass-or-fail
Sno =int(input('enter sno :'))

Sname=input('enter name : ') 

group=input("enter group : ") 

S1=int(input('enter 1st marks : ')) 

S2=int(input('enter 2 nd marks : '))

S3=int(input('enter 3rd marks : ')) 

S4=int(input('enter 4th marks : ')) 

S5=int(input('enter 5th marks : ')) 

S6=int(input('enter 6th marks : ')) 

total = S1+S2+S3+S4+S5+S6 

print('total : ',total) 

avg = total/6 

print('avg : ',avg) 

if avg<35:     
print('Fail') 

elif avg>91:     
print('passed with O grade ') 

elif avg>81:      
print('passed with A grade') 

elif avg>71:     
print('passed with B grade') 

elif avg>61:     
print('passed with C grade') 

elif avg>51:     
print('passed with D grade') 

else:     
print('Pass')
