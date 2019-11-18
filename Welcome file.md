
GURU NANAK DEV ENGINNERING COLLEGE LUDHIANA
            
                        PRACTICAL FILE
                        
                   PROGRAMMING FOR PROBLEM SOLVING
``                   ![](https://lh3.googleusercontent.com/KSq85DP7pVcRXocv0Q0NUnzX14OInzveyzjtfc7n9fnKXB7f34lt4iiWbBmjp2RAxiyvLI_97Ss "kk")
                       
                 
              SUBMITTED TO          SUBMITTED BY
             RANJODH MAM            JASLEEN KAUR
                                         1921049
                                         IT A2
                                         
                                
                                
                           
 PROGRAM 1
                             
                         PRINT A TABLE
  ```c                 
       #include<stdio.h>
       int main()
       {
           int n;
           printf("enter a number:");
           scanf("%d",&n);
           for(i=1;i<=10;i++)
           printf("%d X %d=%d\n",n,i,n*i);
           return(0);
       }
```       
       
       
       ouput
``         ![](https://lh3.googleusercontent.com/Pj_ySZjLHXVY23JdC33aYzYWXkxx0GSVBKa7ECckf8ygrKacb3AQoK34c722QqSOUciSAodmEfI "pp")
       
       
                          program 2
               convert temperature from fahrenheit to celsius
  ```c
            #include<stdio.h>
            int main()
            {
                 float fahrenheit,celsius;
                printf("Enter temperature in fahrenheit:")
                scanf("%d",&fahrenheit);
                celsius=(fahrenheit-32)*5/9;
                printf("\n temperature in celsius is%f",celsius);
                return(0);
            }
```
            
            output
``
![enter image description here](https://lh3.googleusercontent.com/cIBGI_AtKj-xMxFIwtxQNX993PFe3A8nuB_ZlbPFAdhotUgoNXrgssNiGYTQIbnYmwfs0ROLI2g "kk")       

                            program 3
                   To print prime numbers  
  ```c
        #include<stdio.h>
        int main()
        {
        int n,i,p;
        printf("\n enter n value:");
        scanf("%d",&n);
        {
        for(i=2;i<n;i++)
        if(n%i==0)
        p=1;
        }
        if(p==1)
        printf("number is not prime");
        else
        printf("number is prime");
        return(0);
        }
```                    
 output
 ``
 ![enter image description here](https://lh3.googleusercontent.com/Qobh5u6kjsTfozp3sQZtdnvldD3OePg8WYUSelp40PMlHnMwFldmjAHfrVWEi7lAYF3P29yoI3s "ppp")
            
                           program 4
                  to print prime numbers in range 
                               
```c
#include<stdio.h>
int main()
{
int i,j,s,e,p;
printf("Enter a starting number:");
scanf("%d",&s);
printf("Enter ending number:");
scanf("%d',&e);
for("i=s;i<=e;i++)
{
p=0;
for(j=2;j<i;j++)
{
if(i%j==0)
{
p=1;
}
}
if(p==1)
printf("\n %d are not prime",j);
else
printf("\n %d are prime",j);
}
return(0);
}```
                                 output
```
![](https://lh3.googleusercontent.com/1olVYDX5u8OtaKADaLSx17rw9V2CU6hx8McTnlk4Kn6Vb7hlJXJ4gz1hC1f_2OezLM7Lqa8MveU "rr") 

 program 5
                           to find factorial of a number
```c
#include<stdio.h>
int main()
{
int n,i,fac=1;
printf("Enter a number:");
scanf("%d",&n);
{
for(i=1;i<=n;i++)
fac=fac*i;
printf("%d is factorial of %d",fac,n);
}
return(0);
}```

output
```
![enter image description here](https://lh3.googleusercontent.com/cxTgl-F942BZpomElgLi-rZ0xmpxYEr41fG9A9wjdcYlX5mRrNsA9hUcRvkIs19OYXW9TLR3QqQ "hhh")    

program 6 
                            matrix addition
```c
#include<stdio.h>
int main()
{
int m,n,c,d,first[10][10],second[10][10],sum[10][10];
printf('Enter a number of rows and columns of matrices:");
scanf("%d%d,&m&n);
printf("Enter elements of first matrix\n");
for(c=0;c<=m;c++)
for(d=0;d<n;d++) 
scanf("enter elements of second matrix\n");
for(c=0;c<m;c++);
for(d=0;d<n;d++);
scanf("%d",&second[c][d]);
printf("sum of entered matrices:\n);
for(c=0;c<m;c++)
{
for(d=0;d<n;d++)
{
sum[c][d]=first[c][d]+second[c][d]);
}
printf("\n");
return(0);
}```
output
```
![enter image description here](https://lh3.googleusercontent.com/_UZpEPypJlwVRAVbXd6r5VgU-EsJlNimMzleYNGMUKJTcF4zXPZB6fBJQa29eatWd54UUtraTHM "fff")

program 7
                     to print an even table
 ```c
 #include<stdio.h>
   int main()
   {
   int i,n;
   printf("Enter a number:");
   scanf("%d",&n);
   if(n%2==0);
   {
   for(i=1;i<=10;i++)
   {
   printf("%d X %d=%d\n",n,i,n*i);
   }
   }
   else
   printf("Not an even number");
   return(0);
   }``
                output
```
![enter image description here](https://lh3.googleusercontent.com/qpYHePyMAkrGKywTG0LkJaHGLtydPQH20Yrneei9R938TFDTmdWpTkDCGvOCyf_bv24kLsI0u0Q "ee")  

progarm 8 
                     to check whether a number is positive or negative
```c
#include<stdio.h>
int main()
{
int n;
printf("Enter a number:");
scanf("%d",&n);
if(n>0)
printf("number is positive");
else
printf("number is negative");
return(0);
}```
   output
```
![enter image description here](https://lh3.googleusercontent.com/Xeld9QPqQlZS80wbiJHm1kBcOiTy-3AHQdk_gcfNMqT4M6kGo6axMCjSNbUqcFCkZXQS30tNVHo "qq")   
   
       program 9
                to check whether a number is even or odd
```c
#include<stdio.h>
int main()
{
int n;
printf("Enter a number");
scanf("%d",&n);
if(n%2==0);
printf("Number is even");
else
printf("Number is odd");
return(0);
}```
  output
 ```
 ![enter image description here](https://lh3.googleusercontent.com/t6LDtS6RzCeSLMT4I59jYWSpB9ABpERWURsdv6wh2LGVPz4FzvrGkF7M9g2hBgwG9DKd_CCywjI "tt")                                  
                                                          
program 10
                       factorial by recursion
```c
#include<stdio.h>
int multiplynumbers(int n)
int main()
{
int n;
printf("Enter a positive number:");
scanf("%d",&n);
printf("Factorial of %d=%d",n,multiplynumbers(n));
return(0);
}
int multiplynumbers(int n)
{
if(n>=1)
return n*multiplynumbers(n-1);
else 
return 1;
}```
output
```
![enter image description here](https://lh3.googleusercontent.com/QZtCWUMuJaF-pT7cvoU6siIy6X0Bt8ZO4AkDlpKlQTO9osxNhAoiYlYzKgWDM1tVL8wapz8QZ5yA "uu")
 
 program 11
                                    printing pattern
```c
#include<stdio.h>
int main()                                                            
{
int i,j,rows;
printf("Enter no. of rows");
scanf("%d",&rows);
for(i=1;i<=rows;i++)
{
for(j=1;j<=i;j++)
{
printf("*");
}
printf("\n");
}
return(0);
}``
output
```
![enter image description here](https://lh3.googleusercontent.com/7dBL6FBos87r6CvrCABDHP1nfae_Z_o0Xbv5wG9wX2umQTSKblVa8znAqv9kbs0Nzzz_hsGUNjub "zz")     

program 12
                                         Matrix multiplication
```c
#include<stdio.h>
int main()
{
int matA[2][3],  matB[3][4],matR[2][4];
int i,j,k;
printf("Enter elements of 1st matrix 2x3\n");
for(i=0;i<2;i++)
{
for(j=0;j<3;j++)
{
scanf("%d",&matA[i][j]);
}
}   
 printf("Enter elements of 2nd matrix 3x4\n");
for(i=0;i<3;i++)
{
for(j=0;j<4;j++)
{
scanf("%d",&matB[i][j]);
}
}

for(i=0;i<2;i++)
{
for(j=0;j<4;j++)
{
matR[i][j]=0;
}
}          
for(i=0;i<2;i++)
{
for(j=0;j<4;j++)
{
for(k=0;k<3;k++)
matR[i][j]=matR[i][j]+matR[i][k]*matB[k][j];
}
}
}
printf("Matrix multiplication is \n");
for(i=0;i<2;i++)
{
for(j=0;j<4;j++) 
{
printf("%d\t",matR[i][j]);
}
printf("\n");
}
return(0);
}```
output
```
![enter image description here](https://lh3.googleusercontent.com/waJQJ-xdputDIMRIhyF1islDwP28C9qyRxMeQOJMX8IMOElpG3fp2U1VgL4eS2Y_-UmJGkFVEwx6 "nnp")   

program 13
                        
                          
```c
#include<stdio.h>
#define MAX_SIZE 1000
void printArray(int arr[],int len);
int main()
{
int arr[MAX-SIZE];
int even[MAX-SIZE],odd[MAX-SIZE];
int evencount, oddcount;
int i,size;
printf("Enter size of the array:");
scanf("%d",&size);
printf("Enter elements in the array:");
for(i=0;i<size;i++)
{
scanf("%d",7arr[i]);
}
evencount=0;
oddcount=0;
for(i=0;i<size;i++)
{
if(arr[i]&1)
{
odd[oddcount]=arr[i];
oddcount++;
}
else
{
even[evencount]=arr[i];
evencount++;
}
}
printf("\n Elements of even array:\n");
printArray(even,evencount);
printf("\n Elements of odd array:\n");
printArray(odd,oddcount);
return(0);
}
void printArray(int arr[],int len)


                                                                                                                     
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTY3MDU1NTk5LC03NTY5NzcwMDldfQ==
-->