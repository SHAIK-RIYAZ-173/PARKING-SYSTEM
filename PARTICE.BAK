#include<stdio.h>
#include<conio.h>
#define max 5
void display();
void bike();
void car();
void auto1();
void del();

int top=-1,noofbike=0,amount=0,count=0,noofcar=0,noofauto=0,no;
void main()
{
int ch;
clrscr();
while(1)
{
printf("\n1.enter bike");
printf("\n2.enter car");
printf("\n3.enter auto");
printf("\n4.display");
printf("\n5.remove the vehical");
printf("\n6.exit");
printf("\nenter your choice\n");
scanf("%d",&ch);
switch(ch)
{
 case 1:
 bike();
 break;
 case 2:
 car();
 break;
 case 3:
 auto1();
 break;
 case 4:
 display();
 break;
 case 5:
 del();
 break;
 case 6:
 exit(0);
 break;

 default:
 printf("invalid");
 }
 }
 getch();
 }
 void del()
 {
 int ch;
 if(top==-1)
 printf("\nno vehicles are there to display\n");
  else
  {
 printf("\npress 1 to delete bike\n");
 printf("\npress 2 to delete car\n");
 printf("\npress 3 to delete auto\n");
 printf("enter the choice\n");
 scanf("%d",&ch);
 switch(ch)
 {
 case 1:
 if(noofbike==NULL)
 printf("\n no bike are there to delete\n");
 else
 {
 printf("\nbike is deleted\n");
  noofbike--;
   amount=amount-10;
    count--;
    top--;
    }
  break;
  case 2:
  if(noofcar==NULL)
  printf("\nno cars are there to delete\n");
  else
  {
  printf("\ncar is deleted\n");
 noofcar--;
  amount=amount-20;
 count--;
 top--;
 }
 break;
 case 3:
 if(noofauto==NULL)
   printf("\nno auto are there to delete\n");
   else
   {
 printf("\nauto is deleted\n");
  noofauto--;
   amount=amount-30;
 count--;
 top--;
 }
  break;

 }

  }
     }
void display()
{
printf("\nno of bike is %d",noofbike);

printf("\nno of car is %d",noofcar);
printf("\nno of auto is %d",noofauto);
printf("\ntotal no of vehicals is %d",count);
printf("\ntotal amount gain is %d",amount);

}

void bike()
{
if(top==max-1)
printf("parking is full\n");
else
{
printf(" bike entery successful\n");
printf("\n1.2hrs\n2.morethan 2hrs\n3.1hur\n");
printf("enter how many hours do u want\n");
scanf("%d",&no);
switch(no)
{
case 1:
noofbike++;
amount=amount+30;
count++;
top++;
break;
case 2:
noofbike++;
amount=amount+50;
count++;
top++;
break;
case 3:
noofbike++;
amount=amount+10;
count++;
top++;
} }}
void car()
{
if(top==max-1)
printf("parking is full\n");
else
{
printf("car entery successful\n");
noofcar++;
amount=amount+20;
count++;
top++;
}}
void auto1()
{
if(top==max-1)
printf("parking is full\n");
else
{
printf("auto entry successful\n");
noofauto++;
amount=amount+30;
count++;
top++;
}}



