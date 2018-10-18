/*
**********************************************************************
**Author:      Ramanujam Gond                                       **
**Date:        Oct-19-2018                                          **
**Git:         https://github.com/ramanujamgond                     **
**Description: Basic C++ program to display the biodata of author.  **
**********************************************************************
*/

#include <iostream>
using namespace std;

//function declaration for biodata
void biodata();

int main() {
  char inputCharacter;    //declare character variable
  cout <<"Press 'B' or 'b' to see biodata: ";   //Statement for option
  cin >>inputCharacter;   //Option Input

  //Condition to check if user has entered lower Case or Upper Case 'B' character
  if (inputCharacter == 'B' || inputCharacter == 'b') {
    biodata();    //function calling
  } else {
    cout <<"\nInvalid Charcter! Press 'B' or 'b'. \n";    //Statement for invalid input
  }
  return 0;
}

//function definition for biodata
void biodata() {
  cout <<endl;
  cout <<"*************************** USER DETAILS *****************************\n";
  cout <<"**Name:       ** Ramanujam Gond                                     **\n";
  cout <<"**Graduation: ** Computer Science Engineering (CSE)                 **\n";
  cout <<"**College:    ** Trident Academy Of Technology, Bhubaneshwar, Odisha**\n";
  cout <<"**Job:        ** Freelance Frontend Developer                       **\n";
  cout <<"**Love:       ** Programming                                        **\n";
  cout <<"**Git:        ** https://github.com/ramanujamgond                   **\n";
  cout <<"**Email:      ** ramanujamgond@gmail.com                            **\n";
  cout <<"**********************************************************************\n";
  cout <<endl;
}
