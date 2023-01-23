# CPP
==> To write string with spaces we have to use getline(cin,variable name)
==>Data Types
==========
1.int,long,long long.
2.float,double.
3.char,string.
==> to print required number of decimal values
cout<<fixed<<setprecision(decimal values)<<float name



Operators
=========
1.Arthmetic (+,-,*,/,%,)
x%y=== 0 to y-1
2.Assignment(++a,a--,*=a)
3.Relational(==,<<,>>,<=,>=,!=)
4.Logical(&&,||)
5.bitwise(&,|,^,>>,<<)
if any number shift by 1 it is /2
if left shift *2
10>>2,n=2
10/2^n
==for every odd number and operator with 1 the result is 1
1<<p-1


======
LOOPS:
======
=====
Strings (#include<string>)
====
string name.empty() to check whether the string is empty or not.
append is used in cpp
to clear we have string name.clear()
lexographically smaller(123,231 123 is smaller) s1.compare(s2)
to find a sub string in a string (s1.find("abc"))
to remove one word only (s1.erase(first index,first index+len(word))
-----------------------------------
HOW TO ITERARTE A STRING
-----------------------------------
1.for(int i =0;i<string name.size(),i++){
cout<<string name[i];
}
2. for(auto it:string name){
cout<<it;
}



HASH

====
== to avoid collision by using chain structure
== map<key type,value>mpp;

STL LIBRARY
==============================================================================================
1.SEQUENTIAL CONTAINER
--------------------------------

VECTOR
======
== push_back
== pop_back
== A.insert(A.begin()+1,100)
== A.erase(A.begin()+1,100)
== reverse (A.begin(),A.end());
==sort(A.begin(),A.end());
==auto i =A.rbegin();==> last element

LIST(doubly linked list)
==============
list<int>b;
== push_front(i)
==push_back(i)
==pop_front(i)
==push_back(i)

DEQUE
=====
deque<int>a;
push_front
pop_front
push_back
pop_back
d.back();//last element
d.front();//front element

ARRAY
=====
#include<array>
array<int,size>name={data};
arr.empty();

FORWARD LIST (Single Linked List)
======================

2.CONTAINER ADOPTERS
------------------------------

