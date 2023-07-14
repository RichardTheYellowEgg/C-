# C++
##revision 3
/*#include <iostream>

int main()
{
    std::string words="what";
    std::string* ptr=&words;
    std::cout<<words<<"\n";
    std::cout<<&words<<"\n";
    std::cout<<ptr;
    return 0;
}*/
/*#include <iostream>

int main()
{
    std::string words="text";
    std::string* ptr=&words;
    std::cout<<ptr<<"\n";
    std::cout<<*ptr;
    return 0;
}*/
/*#include <iostream>

int main()
{
    std::string words="text";
    std::string* ptr=&words;
    std::cout<<ptr<<"\n";
    std::cout<<*ptr<<"\n";
    *ptr="wording";
    std::cout<<*ptr<<"\n";
    std::cout<<ptr;
    return 0;
}*/
/*#include <iostream>

void myFunction();
int main()
{
    myFunction();
    return 0;
}
void myFunction()
{
    std::cout<<"waffle";
}*/
/*#include <iostream>

void myFunction()
{
    std::cout<<"i need to sleep"<<"\n";
}
int main()
{
    myFunction();
    myFunction();
    myFunction();
    myFunction();
    myFunction();
    myFunction();
    return 0;
}*/
/*#include <iostream>
void mySelf(std::string fname, int age)
{
    std::cout<<fname<<" nguyen "<<age<<" years old"<<"\n";
}
int main()
{
    mySelf("richard",12);
    mySelf("someone",12);
    mySelf("a child",12);
    return 0;
}*/
/*#include <iostream>

int sum(int x)
{
    if(x>0)
    {
        return x + sum(x-1);
    }
    else
    {
        return 0;
    }
}
int main()
{
    int result=sum(10);
    std::cout<<result;
    return 0;
}*/
