# Task 2A

##### Question 1. Difference between C and C++ ?

C was developed before C++ and we can say C++ contains what C lacked. C is a procedural programming language whereas C++ is a object oriented programming language. Now what does this mean, since C++ contains both procedural programming language and OOPS it contains many features that C don't because it being only procedural programming language. procedural programming is what we can say is function driven language or in reference to object oriented programming we can say C is function oriented language. Basically, C is a subset of C++. This also means most of the codes of C++ will run on C but not the other way around. Therefore, C++ is a hybrid of what C had i.e. procedural  programming and it also had OOPS. Now, why did they add object oriented programming, what does it bring to the table, the concept under object oriented programming are encapsulation, polymorphism and inheritance. Encapsulation helps us making and using class and C++ also supports operator and function overloading. Overall C++ is better than C because it has what C lacked.

##### Question 2. What is this operator( : : ) in C++ and what's is it's use ?

This operator is called scope resolution. it can be used as both unary and binary. Basically it is used to refer to the hidden variable due to different. For example if there is a local variable and a global variable of the same name, then to use the global variable  we use the ( : : ) operator to refer to the global variable.

##### Question 3. Are C++ strings mutable or immutable ?

Yes the strings in the  c++ are mutable. Meaning we can change them, append new stuff to them and remove a part of it. Just like how we played with a list in python. C++ allows us to do the same with strings.

##### Question 4. What are namespaces in C++ and their use ?

 To explain this concept simply, we'd start thinking by how any variable or a function is treated in the program. If there is a function, then what's inside of that function is called a group or that function or local to that function, or in the same way there is class whatever is inside it is local to that class. But if there is nothing it  is treated as global. Now inside this global space what if we take a space and name it. In the same way we can make many groups in that global space. So this grouping of set of commands to which groups them under some name is called **namespace**.

##### Question 5. write a program in C++ to print the following pattern ?

#include <iostream>
using namespace std;

int main()
{
   int rows, i, j, space;

   cout << "Enter number of rows: ";
   cin >> rows;

   for(i = 1; i <= rows; i++)
   {
      //for loop for displaying space
      for(space = i; space < rows; space++)
      {
         cout << " ";
      }
      //for loop to display star equal to row number
      for(j = 1; j <= (2 * i - 1); j++)
      {
         cout << "*";
      }

      cout << "\n";
   }

   return 0;
}

##### Question 6. why do you think C++ is the right choice to begin programming ?

C++ might be a difficult language comparably, but it is the most powerful language. It makes you learn what actually happens inside the computer i.e. how computer processes any command like what happens inside the computer how it handles any command or any data type or structure how is it handled by the computer, you get the better knowledge of all this if you're learning C++ and learning and knowing all this is very important. This knowledge helps you to debug your program and moreover it  helps you to be a  better programmer, you can't be a good programmer without knowing what's happening. C++ is more flexible and more resourceful language. It's like we control everything while working with C++. We're in the driver seat with C++ which clearly increases our knowledge. With C++ you can try a lot of different techniques of your own. 