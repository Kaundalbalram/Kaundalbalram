// #include<stdio.h>
// int main(){
//     int i;

//     for (i = 0; i < 10; i++)
//     {
//         printf("%i\n",i);
//     }
    
// }


// // even number
// #include<stdio.h>
// int main(){
//     int i;

//     for (i = 0; i <= 50; i=i+2)
//     {
//         printf("%i\n",i);
//     }
    
// }

//odd number
// #include<stdio.h>
// int main(){
//     int i;

//     for (i = 1; i <= 50; i=i+2)
//     {
//         printf("%i\n",i);
//     }
    
// }

// 3 table
//  #include<stdio.h>
// int main(){
//     int i;- 👋 Hi, I’m @Kaundalbalram
2
- 👀 I’m interested in ...
3
- 🌱 I’m currently learning ...
4
- 💞️ I’m looking to collaborate on ...
5
- 📫 How to reach me ...
6
​
7
<!---
8
Kaundalbalram/Kaundalbalram is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
9
You can click the Preview link to take a look at your changes.
10
--->
11


//     for (i = 3; i <= 30; i=i+3)
//     {
//         printf("%i\n",i);
//     }
    
// }

// 7 table
// #include<stdio.h>
// int main(){
//     int i;

//     for (i = 7; i <= 70; i=i+7)
//     {
//         printf("%i\n",i);
//     }
    
// }

//factor no program
// #include<stdio.h>
// int main (){
//     int i;
//     for(i=1;i<=45;i++){
//         if (45%i==0){
//             printf("%d\n",i);
//         }
        
//     }
// return 0;
// }

//AP series
// #include<stdio.h>
// int main (){
//     int i,num,number ,digit,e,f;
//     printf("Enter your first Digit");
//     scanf("%d",&num);
//     printf("Enter your common difference");
//     scanf("%d",&number);
// printf("Enter your last digit");
// scanf("%d",&digit);

//     for(i=1;i<=10; i++){
//         e=num;
//         f=i+number;
//         printf("%d,",f);
         
    
//     }
// }
//Fibonacci series
// #include<stdio.h>
// int main (){
//     int i,first, second=1,thard;
//     for(i=1;i<=20; i++){
//         thard=first+second;
//         first=second;
//         second=thard;

//         printf("%d,",second);
//     }
   
// }

//paling drone number
// #include<stdio.h>
// int main(){
//     int a=256,b,c,d,e,r;
//  r=a%10;
//  b=a/10;
//  c=b%10;
//  d=b/10;
//  e=b%10;
    

//     printf("sum of three number %d %d %d",r,e,d);
// }

// recerse no program

// #include<stdio.h>
// int main (){
//     int num=131,a;
//     a=num%10;
//     printf("%d",a);
//     a=num/10;
//     a=a%10;
//      printf("%d",a);
//     a=num/10;
//     a=a/10;
//     printf("%d",a);
// }

//palingdrome no program

#include<stdio.h>
int main (){
    int i,rev,num,rem;
printf("Enter your no");
scanf("%d",&num);
for (size_t i=num; i>0; i=i/10)
{
    rem=i%10;
rev=rev*10+rem;

  
}
if(num==rev){


printf("no is palindrome");
}
else{
    printf("no is not palindrome");
}
}
