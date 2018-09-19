# ch3-drill-write-a-letter-
#include "std_lib_facilities.h"
int main()
{
cout<<"Please enter your first name!\n";
string fn;
cin>>fn;
//cout<<"Hello, "<<fn<<"!\n";

//1. feladat
cout<<"Enter the name of the person you want to write to!\n";
string recipiant;
cin>>recipiant;
cout<<"Dear "<<recipiant<<",\n";


//2. feladat
cout<<"\nHow are you? I'm a little bit nervous because I moved to\nDebrecen a week ago and everything is so new for me. I miss you.\nIt was long time ago when we met.\n";

//3. feladat
cout<<"\nPlease enter your friend name?\n";
string friend_name;
cin>>friend_name;
cout<<"\nHave you seen "<<friend_name<<" lately?\n";

//4. feladat
char friend_sex = 0;
cout<<"\nIs your friend a male or a female? (m/f)\n";
cin>>friend_sex;
if (friend_sex == 'm')
cout<<"If you see "<<friend_name<<" please ask him to call me.\n";
if (friend_sex == 'f')
cout<<"If you see "<<friend_name<<" please ask her to call me.\n";

//5. feladat
int age;
cout<<"\nHow old is your friend?\n";
cin>>age;
cout<<"\nI have heard you just had a birthday and you are "<<age<<" years old.\n";
if (age <= 0 or age >= 100)
simple_error("You are kidding!");

//6. feladat
if (age < 12)
cout<<"Next year you will be "<<age+1<<".\n";
if (age == 17)
cout<<"Next year you will be able to vote.\n";
if (age > 70)
cout<<"I hope you are enjoying retirement.\n";

//7. feladat
cout<<"\nYours sincerely,\n\n\n"<<fn<<"\n";
} 
