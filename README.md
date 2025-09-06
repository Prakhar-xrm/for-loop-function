#include <stdio.h>
int main(){
  int num, sum = 0;
  for(int num=1; num<=50; num++){
    sum = sum + num;
  }
  printf("%d\n", sum);
  return 0;
}
