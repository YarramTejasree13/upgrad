# upgrad
class palindrome
{
public static void main(string[] args)
{
int r,sum=0,temp;
int n=454;
temp=n;
while(n>0)
{
r=n%10;
sum=(sum*10)+r;
n=n/10;
}
if(temp==sum)
System.out.print("the number is palindrome");
else
System.out.print("the number is not a palindrome");
}
}
