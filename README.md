# 2205142_prime_number
to check weather it is a prime number or not
#include <stdio.h>
int main()
{
  int i,no,c;
  printf("Enter the positive number ");
  scanf("%d",&no);
  for(i=1;i<=no;i++){
    if(no%i==0){
      c++;
    }
  }
  if(c==2){
    printf("Its a prime number");
  }
  else{
    printf("Its not a prime number");
  }
  return 0;
}
