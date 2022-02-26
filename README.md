# assignment-2.-25-02-22

count=0
pos=0
neg=0
while(count<5):
    num=int(input('enter a number:'))
    if(num==0):
        break;
    elif(num>0):
        pos=pos+1
    else:
            neg=neg+1
            count=count+1
print("count of positive number is",pos)
print("coutn of negitive number is",neg)
