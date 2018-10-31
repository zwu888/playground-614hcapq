# 
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

# Advanced usage

If you want a more complex example (external libraries, viewers...), use the [Advanced C++ template](https://tech.io/select-repo/598)
