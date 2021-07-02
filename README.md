# Basic_Codes



## Leap Year Or Not ##



```
#include <iostream>
using namespace std;

int main() 
{
  int y;
  std::cin>>y;
  if(y%4==0&&y%100!=0||y%400==0)
    std::cout<<"Leap Year";
  else 
    std::cout<<"Not a Leap Year";
   // Try out your code here
}
```


