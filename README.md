

#include <iostream>

using namespace std;

struct Marks
{
    short physics;
	short informatics;	
	short history;
	bool isCorrect(){
	    bool value = false;
	    if( (physics && informatics && history) <=10) value =  true;    
	   }
};

struct Student 
{
	char surname[56];
	short group;
	Marks progress;
};


int main()
{


    return 0;
}
