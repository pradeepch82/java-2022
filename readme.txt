Applications/Software/Product
-------------------------------------------
1.Standalone/Desktop   Appplication
2.Mobile Applications
3.Web Application
4.Hybrid Applications


What are the enterprises/business org?

Enterprise :(Business Organization) : make the money by providing services
===================================
Banks  :withdraw,deposit,fundTransfer,loan
LICS   :Insurance policy
Transports:book,cancel ticket
Hotels  :order food,book table
Hospitals:appointment
School   :admission,teaching,result
College  :admission,teaching,result

Why we develop the enterprise applications?

To assisst the businees
To grow the business
To ease the business
To reach out to our customer

Every Enterpise application is divided into 4 layers?

1.Presnetnation Layer  : It's a code written to dsiapy the input screen as well as output screen to the user.
 
                                    Hello Pradeep
                                    Hello Saurabh
                      Static Content:  Hello
                      Dynamic Content : Pradeep,Saurabh


2.Service Layer /Business Logic Layer :
                         It is a logical implementation of business rules.

                            class Bank{

                                         fundTransfer(int source,int dest,int amount){

                                           //if source exists && dest exists && amount to be transfered is leass than avaiable bance
                                           //debit the source account by amount
                                           //credit the destinatio account by amount
                                          //commit the changes in database
                                          //dsisplay the successfull message
                                         else
                                          //display error Problem in transfering the fund   
                          
                                      }
                 }

                                      



3.Data Access Layer
                    The code written to access the data from DataSource is called as Data Access Layer.

C  - Create the record
R -  Read/Retrieve the record
U -  Update the record 
D -  Delete the record


          
4.Data Layer


Layer   : Logical separation of the code.


Tier  : Physical sepration of the code 

           1 tier application
           2 tier application
           3 tier application
           n tier application

Requirements Business
----------------------------------
1.Capital
2.Resources (employees,data)
3.Infra
4.Rules/Specification

What are the different platform to develop the applications?
1.Java
2.Net
3.Python
4.PHP


Java 
------
JavaSE       :Java Standard Edition   :Stand alone application   (Core Java)

JavaEE      : Java Enterrpise Edition   : Enterprise application  (Advance Java)

JavaME     :Java Mobile Edition            : Mobile Application

------------------------------------------------------------------------------------------------

JDK 8
=====
https://www.oracle.com/java/technologies/javase/javase8-archive-downloads.html#license-lightbox

or

https://drive.google.com/file/d/1zXJcNOxU9CtKV0bB7F4OU19Fv1t05ugk/view?usp=sharing


STS Download
============
https://dist.springsource.com/release/STS/3.9.11.RELEASE/dist/e4.14/spring-tool-suite-3.9.11.RELEASE-e4.14.0-win32-x86_64.zip

Spring Distrubution 5.0
=======================
https://repo.spring.io/release/org/springframework/spring/5.0.2.RELEASE/

or

https://drive.google.com/file/d/1zXJcNOxU9CtKV0bB7F4OU19Fv1t05ugk/view?usp=sharing


day2:15-05-2022
-----------------------
OOPs features
--------------------------
1.Class
2.Object
3.Encapsulation
4.Inheritance
5.Polymorphism
6.Abstraction
7.Message Communication

 
Object Programming
----------------------------
Object based Programing   : Object,Class,Encapsulation  : VB Script ,JavaScript 

Object oriented Programing :



class      (properties & behaviours/actions )         object  (properties & behaviours/actions )

Animal                                                                dog,cat,horse                                  color,height                  sleep,eat
Actor                                                                   Dharmendra,Amitabh                     name,age,address       dance,sing,fight,act
Breakfast                                                            Idly,Puri,Poha                                 name,color,shape        taste
Furniture                                                             Table,Chair,Cubboard                    color,shape,price         
Device                                                                 Mobile,TV,Laptop                          color,company             switch on,switch off
Flower                                                                 rose                                                color,shape                  smell 
Singer                                                                 Lata,Rafi,Kishore                           name,age,address        sing 
Company                         
Employee
Product


class  <classname>
{
//properites
datatype variable1;
datatype variable1;
datatype variable1;

//behaviours
returntype method1();
returntype method1();
returntype method1();
returntype method1();
}


Object
----------

<classname>   objectname=new <classname>();

objectname.variable1;
objectname.variable2;
objectname.variable3;
objectname.variable4;

objectname.method1;
objectname.method1;
objectname.method1;
objectname.method1;


1.Write a class Employee with below properties & methods and create a object and to set and display employee details;

Employee
        id
        name
        salary

setter   //to set the values
getter  //to read the values


Java Premitive Datatypes
-------------------------------------
byte
short
int
long

float
double

char
boolean


java.lang.Object is the default super class for all the classes in Java.


1. Student
          id
          name
          marks
           
            //constructor
           //setter && getter
           //toString   

2.Circle
          radius

           //constructor
           //setter && getter
           //toString   
                       
         area()
         peri()  


2.Rectangle
          length
          breadth
        
         //constructor
           //setter && getter
           //toString   
                       
         area()
         peri()  

3.Square
          side
        
         //constructor
           //setter && getter
           //toString   
                       
         area()   4*4
         peri()    4*side


4.Traingle
          
           side1
           side2
           side3
        
         //constructor
           //setter && getter
           //toString   
                       
         area()   4*4
         peri()    4*side


5.Spehere
          
            radius
          
         //constructor
           //setter && getter
           //toString   
                       
          volume();

6.cylinder
          
            radius
            height
          
         //constructor
           //setter && getter
           //toString   
                       
          volume();
         




















