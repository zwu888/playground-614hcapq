# description: 
 Distinct pointer types can not be compared with equality operators
```C++ runnable
#include <iostream>

struct Foo
{
};

struct Bar 
{
};

int main(int argc, char** argv)
{
  Foo* f = new Foo;
  Bar* b = new Bar;

  if ( f == b )
    std::cout << "EQUAL" << std::endl;
  else
    std::cout << "NOT EQUAL" << std::endl;

  return 0;
}
```

