// cpp
//Area calculator 
//Calculate of various  Areas
#include<iostream>
#include<stdlib.h>
using namespace std;

class student
{   float side;
    float length;
    float breadth;
    float radius;

public:
    void square();
    void rectangle();
    void circle();
    void triangle();
};
void student::square()
{
    cout<<"enter side:.";
    cin>>side;
    cout<<side*side<<"\n";
}
void student::rectangle()
{
    cout<<"enter length and breadth";
    cin>>length>>breadth;

    cout<<length*breadth<<"\n";

}
void student::circle()
{
    cout<<"enter radius:";
    cin>>radius;
    cout<<3.14*radius*radius<<"\n";
}
void student::triangle()
{
    cout<<"Enter the length and breadth :";
    cin>>length>>breadth;
    cout<<0.5*length*breadth<<"\n";
}

int main()
{
    student s;
    int c;
    while(1)
    {
        cout<<"\n1.calculate Area of sq\n2.calculate Area of rectangel\n3.area of circle\n4.Area of triangle\n5.exit\n";
        cin>>c;

        switch(c)
        {
        case 1:
            s.square();
            break;

        case 2:
            s.rectangle();
            break;

        case 3:
            s.circle();
            break;
            
        case 4:
            s.triangle();
            break;
            
        case 5:
            exit(0);
            break;

        default:
            cout<<"you put wrong input try again\n";
            break;
        }



    }
    return 0;
}
