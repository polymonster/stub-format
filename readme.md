# stub-format
A python utility script for generating c or c++ function stubs and other simple formatting jobs.

# actions

-generate stub functions
-tabs to spaces
-remove comments
-align characters of consecutive lines

### test.h output
```c++
#include test.h

namespace stub_test
{
    const void* function_a() 
    {
        return nullptr;
    }
    
    void function_b(int param_a, int* pointer, const int& ref) 
    {
    
    }
    
    int my_class::function_c(int param) 
    {
        return int();
    }
    
    const void* my_class::function_d() 
    {
        return nullptr;
    }
    
    int my_class::function_const() const
    {
        return int();
    }
    
    namespace deeper
    {
        void function_e(int a, float b, test c) 
        {
        
        }
        
        int function_f(int b = 0) 
        {
            return int();
        }
        
        int scope_class::function_g(int a, int b, int c = 0) 
        {
            return int();
        }
    }

    void function_h(int b) 
    {
    
    }
}
```
