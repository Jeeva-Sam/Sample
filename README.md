eg input is 1221
Declare four variables.(n,r,sum=0,temp)
Get an input for a variable.(n="input")
Assign the value to another variable.(n=temp)
Initiate a while loop.(while n>0 )
The following code runs the loop :
r=n%10; #gets last digit 1   
sum=(sum*10)+r; #(0*10)+1(r)   
n=n/10;
The while loop executes until the given input is exhausted
Now after the loop,variable sum will get a value 
If the value in sum is equal to variable temp ;
It is a palindrome
Else :
It's not a palindrome
