#include<iostream>
using namespace std;

class TeosClass
{
    /*private variables*/
        int a;
        float b;
    
    public:
        /*initialization of private variables of the class using the constructor*/
        TeosClass (int age, float height)
        {
            a = age;
            b = height;
        }
        
        int get_a ()
        {
            return a;
        }
        
        float get_b ()
        {
            return b;
        }
};

int main ()
{
    TeosClass obj (20, 160);
    cout<< "a = "<<obj.get_a()<<endl;
    cout<< "b = "<<obj.get_b()<<endl;
    
    return 0;
}
