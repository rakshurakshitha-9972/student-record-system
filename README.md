# student-record-system
MCA 1st sem project - Student Record System
# student-record-system
MCA 1st sem project - Student Record System

Student Record System

MCA 1st Semester Project - C Programming

A simple and efficient program to manage student records using Structures in C.
#include <stdio.h>
struct Student {
  int roll;
  char name[50];
  float marks;
};
int main() {
  struct Student s1;
  printf("Enter Roll: ");
  scanf("%d", &s1.roll);
  printf("Enter Name: ");
  scanf("%s", s1.name);
  printf("Enter Marks: ");
  scanf("%f", &s1.marks);
  printf("\n--- Student Record ---\n");
  printf("Roll: %d\nName: %s\nMarks: %.2f\n", s1.roll, s1.name, s1.marks);
  return 0;
}

🎯 Objective
To store and display student information like Roll Number, Name, and Marks.

✨ Features
- Add Student Details
- Display Student Record
- Uses Struct Concept
- Beginner Friendly Code


💻 How to Run
gcc student.c -o student
./student
📝 Sample Output
Enter Roll: 101
Enter Name: Rakshitha
Enter Marks: 92

--- Student Record ---
Roll: 101
Name: Rakshitha
Marks: 92.00
