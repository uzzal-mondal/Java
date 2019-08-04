# Java Master OOP Done

                                                # OOP #
# Tutorial – 1 -> Class & Object.
*	Class:  class holo akti templeate jar maddhome amara onek gulo template create  korte pari.



 
*	Class - Class holo somistogoto vabe onekjoner somonoy: 
*	Class - Class holo akti Template jar theke, ba oi class er properties gulo diye  amara  Object create korte pari.  

*	Object - Class a onotorvukto properites gulo holo object. 


*	Object -  j kono class type er variable kei object bola hoy. 





# Learn class & object: -  
*	Create class > class er moddhe variable declare > sei class er object onno class a declare  korte hoy 

*	object er maddhome kivabe akti class er variable use korte hoy.

*	Akti class er object create kore , sei class er properties gulo use korlam. Oi class er Multi properties o use korte pari oi akoi class er template er maddhome.




# OOP : 2
# Introducing method
 - Method(){} – akoi dhoroner programming er jonno Jodi amra kono akta jinish bar bar  kaj korte chai tahole amra oop te  mehod use korbo.

- Class: class a amra variable then method use kori. Variable use korle onek gulo println use korte hoy, but-   bar bar call korte hoyna just call method call korle hoye jai.  Class a variable er thke method use flexible . 
OOP : 03
Parametrized method
1.	Parameter method use kore amra sob gulo data set  korte pari. 

2.	Method er maddhome data set kora flexible.


3.	Main method a j data gulo thakbe sei data gulo parameter method a call kori.
4.	Variable er sathe data gulo rakte pari.

First step
Teacher teacher1 = new Teacher();
teacher1.teacherInfo("Anisul","CSE",25);
teacher1.displayInfo();





 Teacher teacher2 = new Teacher();
 teacher2.teacherInfo("Uzzal","CSE",20);
 teacher2.displayInfo();


 Teacher teacher3 = new Teacher();
 teacher3.teacherInfo("Sudipto","CSE",22);
 teacher3.displayInfo();








Second step:- 

 //variable create:
 String name;
 String dept;
 int age;

 // paramitarize metod call

 void teacherInfo(String n, String d, int a){

      name = n;
      dept =d;
      age = a;

 }
// simple metod create

 void displayInfo(){

      System.out.println(" name : "+name);
      System.out.println(" department : "+dept);
      System.out.println(" age : "+age);
      System.out.println(" ");

 }


# OOP: - 04
# Constructer
Why constructer use: 
Constructer use kora hoy ei karone – when I am create to object then can do it initialize  
jokon object toiri kori take jano initialize korte pari 
 
1.	Constructer initialize kore akta object.
2.	Constructer & class - same name hobe.
3.	Constructer k method bola hoy.
4.	Return type & void don’t use.
5.	Automatically call hoy.
6.	Parameterized constructer.(cons thakbe)
7.	Default constructer(cons thakbena).
8.	Computer automatically call to default constructer.
 constructer kaj holo object ke initialize kora.

 
Step : 1
Teacher teacher1 = new Teacher("Anisul islma","Cse",30);
teacher1.displayInfo();



 Teacher teacher2 = new Teacher("Uzzal","CSE",20);
 teacher2.displayInfo();


 Teacher teacher3 = new Teacher("Sudipto","CSE",22);
 teacher3.displayInfo();

Step: 2
//variable create:
 String name;
 String dept;
 int age;


 //create to Constructer.
 Teacher(String n, String d, int a){

      name = n;
      dept = d;
      age = a;
 }
  //default constructer
 Teacher(){

 }


// simple metod create

 void displayInfo(){

      System.out.println(" name : "+name);
      System.out.println(" department : "+dept);
      System.out.println(" age : "+age);
      System.out.println(" ");

 }






# OOP : 5
# Types of Constructer
# 02 Types  are constructer, 
1.	Default cons – j parameter er moddhe parameter thakbena default cons
2.	 Parametirezed cons – j parmiter er moddhe parameter thakbe. Prametirezed cons.
3.	03 ti  parameter constructer khujbe akti class er 03 ti parameter constructer k.

4.	02 ti parameter constructer khujbe oi akoi class er 02 ti constructer er parameter k.
5.	R Jodi kono faka constructer thake tahole se oi class er  default constructer ke find korbe.  Ter moddhe ja thakbe print korbe.  

6.	Jokon akta default parameter thakbe , r se jokon default constructer ke khujbe, r jokon na pabe, tokon compiler automatic default constructer ke call korbe..  

7.	R akon Jodi amra kono print korar jonno method call kori , ekhane amder jehetu data set kora nai, sehetu  ekhane amder default value null pabe. For string-null , int jonno - 0 ,  double er jono - 0.0

Example:
Teacher teacher = new Teacher("Anisul sir","Khulna",30);
teacher.displayShow();


Teacher teacher1 = new Teacher("Anisul sir","Khulna");
teacher1.displayShow();

Teacher teacher2 = new Teacher();
teacher2.displayShow();

Step: 2

public class Teacher{

     // create to variable

    String name;
    String sName;
    int dClass;

    //create to default constructer
    Teacher(){
         System.out.println("default constructer");
    }

    // create to two type constructer
    Teacher(String n, String sn){
        //value set
        name = n;
        sName = sn;

    }

    // create to three type constructer
    Teacher(String n,String sn, int dc){

        name = n;
        sName = sn;
        dClass = dc;
    }


    void  displayShow(){

        System.out.println("Name : "+name);
        System.out.println("School name : "+sName);
        System.out.println("Day hour class : "+dClass);
        System.out.println("\n");
    }
# OOP : 6
# Constructer Overloading

1.	Default cons -> two parameter cons ->Three parameter cons-> that’s means constructer overloading

Exam: 
Step: 1
//constructer overloading

  Teacher teacher= new Teacher();
  teacher.displayInfo();

  Teacher teacher1 = new Teacher("Shaptami","Education");
  teacher1.displayInfo();

  Teacher teacher2 = new Teacher("Suzal","Sociology",28);
  teacher2.displayInfo();

Step:2
// constructer overloading

//create variable
String name;
String dept;
int age;

//default  constructer
Teacher(){
  System.out.println("default cons");
}

 //two paramiter constructer
Teacher(String n, String d){

    // data set
    name=n;
    dept = d;
}

//three paramiter constructer
Teacher(String n, String d, int a){
    name=n;
    dept = d;
    age = a;
}


void displayInfo(){

    System.out.println("Name: "+name);
    System.out.println("Department: "+dept);
    System.out.println("Age: "+age);

    System.out.println();
}






# OOP - 7
# Returning valu from method
# akti method theke kivabe value return kora jai that’s means Returning value from method 

Example:
 Step – 1
// akta method theke kivabe value return kora jai


 int square(int value){

     return value*value;
 }

Step – 2
ReturningValuefromMethod rt = new ReturningValuefromMethod();
rt.square(5);
System.out.println("Res "+rt.square(7));


ReturningValuefromMethod rt1 = new ReturningValuefromMethod();
rt.square(5);
System.out.println("Res "+rt1.square(10));

OOP – 8
Between Constructer and Method

1.	Constructer must be initialize class name.
2.	Mthod er j kono name create korte pari.
That’s menas user define method.

3.	Constructer implicity no need call for object.
4.	Method explicity must call for object.
 


5.	Constructer must not return type.
6.	Method must be return type at least void.

7.	Constructer maddhome object k initialize korte pari.
8.	Method er maddhome ter behavior/properties gulo Prokash korte pari
 





# OOP 
# Static: 
Why I am use to static keyword.
Static keyword used to memory management. Static keyword use korar fole amara amder memory save korte pari. 

Use to static :)
1.	Static variable.
	Instance variable er jonno alada jaiga nai , karon amader object call korte hoy. Value gulo alada thake. 
	Akta static variable declare kori , setake call deaor projon hoyna, calss area ke refer kore , so that, no need for memory space 
	Static variable use for use no need for create object , just realation to class just call class to main method..
2.	Static block;
 static block execute hoy main method or age. 
 Main method kintuo almost necessary.


3.	Static Method.
main is static method , so that don't create or no need  a object in main method.

static keyword use to static method declare.

static method no need for obj declare in main method, just use to relation in class.

 static method er restriction ache,  static method er moddhe non static method declare kora jabena. amon ki non static variable o declare kora jabena.  
but static hole static method er moddhe declare kora jabe. Static variable hole static method a declare kora jabe.

 non static method there is no  restriction, se static method access korte parbe… 







# OOP - 9
# Static variable: part 1
1.	If I any variable declare to static , that’s means final . non editable. 
Static String uniName = “khulna Universitty”
2.	No need for assign constructer parameter. 
3.	Static variable call by main class er reference.
4.	Static variable automatically call by reference. 
5.	Static variable declare using no need for declare  object. Just use class name.static variable. 
6.	Static string name = “uzzal”; -static
Test t = new Test(); - no need.
staticv.name – need for direct print static.

Step : 1
public static void main(String args[]){

    Student std = new Student("Uzzal",01);
    std.displayMethod(); // call method

    Student std2 = new Student("Suzal",02);
    std2.displayMethod(); //call method
}



step:2
package OOP;

public class Student {

    // create  variable
    String name;
    int id;
    static String universityName = "DIU";

    //constructer

    Student(String n, int i){
        name = n;
        id = i;

    }


    //display method.
    void displayMethod(){

        System.out.println("Name :"+name);
        System.out.println("id :"+id);
        System.out.println("University Name :"+universityName);
        System.out.println();
    }




}


# OOP - 10
# Static variable: part 2
1.	When a use to static variable must declare before to variable – static
static String uName = “DIU”

2.	Static variable use for no need other class object with reference. 
Student std = new Student();- no need

3.	If you use to static variable , call to static variable class and use to  .(dot) with a static variable name.
System.out. println(Student.uName);
       

Step: 1
  public static void main(String args[]){


       // Student std  = new Student();
        System.out.println(Student.uName);

    }

}

Step: 2

public class Student {

     static String uName = "DIU";



}








# OOP - 11
# Static variable: part 3
1.	Non static variable declare for take an another memory space.
int count = 0; // variable declare
Student (){
	count++;      //this call for constructer
}
Student std1 = new Student();
System.out.println(std1.count) //print.
Student std2= new Student();
Student std3 = new Student();

2.	Non static variable use kora hole , alada alda memory space use kore, jehetu amar count variable 0, to bere sekhane 1 hosse. Next joto variable pabe 0 theke 1 hobe. Every object count alada.

3.	Static variable jokon declare korbo, tokon object er sathe relation nei.ti se default constructer ke pabe and initlize man 0 theke 1 barabe. Static variable object er sathe realtion nei just relation for a class.  Then call to method, firstly print 1 , jehetu static variable change noy tai second variable sathe 1 er sathe 1 count hobe, evabe 1, 1 kore joto obj pabe oi class er barte thakbe.

Ex: 1
public static void main(String args[]){


  Student std1 = new Student();
    std1.totalStudent();

  Student std2 = new Student();
  std2.totalStudent();

  Student std3 = new Student();
  std3.totalStudent();

}
Ex: 2
public class Student {

   static int count=  0;

    Student(){
        count++;
    }

    void totalStudent(){

        System.out.println("Total student "+count);
    }

o/p
Total student 1
Total student 2
Total student 3









# OOP : 12
# Static Method.


1.	Static method declare korte no need for object –  must need for a class.
Ex: teacher.showData(); 
Teacher-class, 
showData() – method.

2.	Non static method declare to must be initlize object.  – firstly create class then class er object.
Ex: Teacher t1 = new Teacher();
 T1   - object
t1.showData();


ex: 
step:1
public static void main(String args[]){


    // non static method,
    // 1. must be initilize obj
 Student std = new Student(); //create to obj
std.displayShow();



/*static method.
  1. Don't initilize obj
  2. must call to class
  3.  . then call method.

   */

    Student.staticResShow();


}


step: 2
package OOP;

public class Student {

  //static method

    void displayShow(){

        System.out.println("Non static method");
    }


       static void staticResShow(){

        System.out.println("Static method ");

       }

}



# OOP - 13
# Static method Restrictions
 

1.	 Static method er moddhe kono -  non static method , non static variable with every things non static kisui declare kora jabena  -  static method er moddhe.

2.	 Non static method er modhe  -  static method, static variable declare kora jabe..

3.	Static method er moddhe static method rakhte pari.



Example: 
Step : 1
public static void main(String args[]){

    //static mehod.
    Student.showRes();

    Student std = new Student();
    std.displayShow();


}


step: 2
public class Student {

  //static method

   static int a = 10;

    //local mehtod
   void displayShow(){

       showRes();
       System.out.println("non static mehod");

   }

  static void showRes(){

       a  = 10;
       System.out.println("Static method");
   }


}








# OOp -14
# Static Block

1.	Static variable ke intilize ba value set korar jonno amara static block use korboo.

Static int n;
Static String name;
Ex:- static{  
     Int n = 10;
String name  = “uzzal”;
}

2.	 Static block – static {       }

3.	 Static block Jodi main method er o age declare kore thake tahole static method ti  main method er agei print hoy.





Example:- 
    public static void main(String args[]){

       /*  Static variable ke intilize ba value set korar jonno amara static block use korboo.

                Static int n;
        Static String name;
        Ex:- static{
            Int n = 10;
            String name  = “uzzal”;
        }

        2.  Static block – static {       }

        3.  Static block Jodi main method er o age declare kore thake tahole static method ti  main method er agei print hoy.

*/



        //static mehod.
        Student.showRes();


        Student.display();


    }

}




step:2
package OOP;

public class Student {

  //static method

   static int a ;
   static String name ;

 // static member initilize to static block;
   static {

       a = 10;
       name = "uzzal";

   }


  static void showRes(){

       a  = 10;
       System.out.println("Static method");
   }

   static void display(){

       System.out.println(a);
       System.out.println(name);
   }


}




# OOp -14
# Types of variable
1.	Local variable. – method er moddhe assign .
2.	Static/class variable. – static keyeword assign hole.
3.	Instance variable – class er modhe but method er moddhe noy abar static declare o noy take instance variable bole.


          
 

 

 


# OOP – 15
# Problem solving

 

Step: 1
public static void main(String args[]){

    Box box1 = new Box(10,10,10);
    Box box2 = new Box(20,30,10);


    box1.displayVol();
    box2.displayVol();
}
Step: 2
package OOP;

public class Box {

    // instance variable.
    double height;
    double width;
    double depth;

     //create a constructer.
    Box(double h, double w, double de){

        height = h;
        width = w;
        depth = de;
    }

    void displayVol(){


        double vol = width*height*depth;

        System.out.println("Box volume "+vol);

    }
}

# OOP – 16
# Instance variable hiding

1.	this.instance  variable use korle instance variable hiding hoyna, local variable kase.

1.	Class er moddhe j variable seta holo instance variable. 
2.	Method er moddhe j variable seta hole local variable.

3.	Local variable er priorty  beshi instance variable er theke.


4.	E jonno local instance variable r local variable use jokon korbo. – this.instance variable = local variable dibo.
                              
5.	Instance variabler age this keyword use korte hoy.






dfgh



OOP – 17
Math Class
1.Math er pore sobguloi method..
System.out.println(Math.abs(-10));
System.out.println(Math.sqrt(25));
System.out.println(Math.pow(3,2));
System.out.println(Math.max(10,5));
System.out.println(Math.min(10,5));
System.out.println(Math.PI);
System.out.println(Math.random());
System.out.println(Math.floor(10));
System.out.println(Math.ceil(10));
System.out.println(Math.log(2));



# OOP – 18
# Method Overloading

 

1.	Java tea akoi namer method declaring korte parbo but tader parameter list must be different 
2.	Parameter list hote pare 2/3 ta with datatype change.


3.	Method overloading ke – 
# Polymorphism, #compile time.  Polymorphism bola hoye thake.

4.	Java tea akoi namer method declare kora jabe but tader parameter gulo change / different  thaka  lagbe  ake bola hoy method overloading. 














5.	Method & parameter aksathe mile amara jeta boli seta ke – method signature boli…

Point overloading:
1.	Same method name
2.	Parameter list are different
3.	Inside the same class. – akoi class er moddhe.

# OOP – 19
# Automatic Type Conversation 


OOP – 20
Debugging in Java

Please see the video… 





# OOP – 21
# Java Argument Passing

1.	 All are primitive data storage to stack value.

2.	 Method er moddhe parameter ke bola hoy – Actual parameter. Class er vitore parameter ke bola hoy formal parameter.

3.	Formal value changeable,  but actual value isn’t chage. 



# Call by value: 01 
1.	Shdharonoto amra jokon akta method theke onno akta mehod e primitive data type argument er maddhome pass kore thaki , tokon orginal value change hobena.

2.	Orthat- actual parameter theke formal parameter data  passing kori, tokon actual parameter er original valur man change hobena ….@

3.	formal parameter a Jodi change hoy tahole seta effect porbena actual parameter a .
Actual parameter not changeable
4.	original value kokono change hoyna that actual parameter er value change hoyna .


# Call By Reference:02
1.	 Class create to call by reference. With string name.

2.	Akti method declare korsi change name, jeta class er object create korse. callByReference holo class r r2 holo object..  

3.	Stack memory :- primitive datatype , reference value gulo storage hoy.

4.	Heap memory te object gulo storage hoye thake.

5.	Call by value te originally value change hoyna , but call by reference a originally value change hoy.


      #   OOP – 22
# Variable Length argument: vargs


1.	Variable length arguments er madhome akadhik argument data passing korte parbo, aktai method create kore. 

2.	Method overloading ba polymorphism er moton amar method ba differ parameter use korar projon hossena. 

3.	 … (3) ta .dot dilei sob gulo data rakte parsi.

Code:- 


# OOP – 23
# Recursion

Recursion:- j method nije nijeke call kore take Recursion, Recursive function bola hoye thake.
Base case:- infinite call cholte thakbe tai call thamonor jonno base case use korbo.
Factorial:  5 :   5*4*3*2*1 = 120
Formula of fac  :     n*(n-1) 
Base case: if(n==1) then return korbe 1 then condition jokon 1 hobe tokon theme jabe.
Recursive call:- else{
            n*fact(n-1)
}



 
Code: recursive function…
 
# OOP – 24
# Iteration vs. Recursion
 
Code : coding code.
 


# OOP -25
# important Tutorial Encapsulation
4 types for Access modifier. Method/class er age bose . birer kono class ke access for use
 
 



Encapsulation:- 
 Kono akta class er variable and method aksahte ba package akare tahakbe akta single unit hishabe  etake amra encapsulation bolbo.
 

Public class Encap{
1.	Package er under a .
// single unit hisabe thakbe 
2.	Variable.
3.	Method.
}




Step-1 variable and ,method gulo akta package er under a single unit hishabe ase r etai holo encapsulation.  
Person- package er moddhe,  variable & method ke single unit a rakhai hose Encapsulation.
 

use: encapsulation er data gulo amara use korbo sohoze person class er akta object create kore, person er maddhoem name, eat , talk  egulo amara use korte parbo.


Two forms are encapsulation:- 
1.	Variable & method gulo single unit a niye asa.
2.	Data gulo ke private hishabe declare kora.





Private data gulo hidden hobe bairer class er jonno, access modifier er maddhome aara use korte pari. This is known as data hiding. Private modifier ke access korte projon hobe, set and getter method, r ei process ke bola hoy data hiding.
1.	Private j video gulo ase eta call korte hole amader set and get method lage.


How do use to encapsulation method:-
1.	 Declaring and variable private.
2.	 Variable er  value gulo value change korar jonno amra setter , getter use korbo. Return korar jonno.




Benefits Encapsulation: -
1.	Data hiding- access modifier.
2.	Reusability-  person class er object onek vabe call korte pari.
3.	 Code modify kora jabe without changing main code kono kisu change na kore.


4.	Maintainability – person calss er moddhe ki ki ase na jene object make kore use korte pari. With object er maddhome name, age properties gulo use korte parsi.

Good news: - 1. Encapsulation create korte hobe variable gulo private korar jonno. 
2.Private variable gulo access korar jono, getter, setter, use korte hobe
OOP -26
Setter and Getter Method

1.	 Encapsulation using to variable must be initialize private , if access to this variable , you must declare getter and setter.

o/p 
uzzal
20


step: 1
package OOP;

public class EncapMain {

    public static void main(String []args){


        Encap en = new Encap();
        en.setName("uzzal");
        en.setRoll(20);

        System.out.println(en.getName());
        System.out.println(en.getRoll());

    }
}


**********************************************************

step : 2
package OOP;

public class Encap {

    private String name;
    private int roll;


    public void setName(String name){

        this.name = name;
    }

    public String getName(){
        return name;
    }

    public void setRoll(int roll){
        this.roll = roll;
    }

    public int getRoll(){
        return roll;
    }
}





# OOP : 27
# Important of Inheritance

Inheritance:-  akta parent class . akta child class ke extends korbe ter properties gulo paoar jonno


Inheritance: - 

	

Inheritance:-  akta parent class . akta child class ke extends korbe ter properties gulo paoar jonno


Coding:--
ICT
Name :uzzal
Age :21



step : 1
package OOP;

public class InheritMain {
    public static void main(String args[]){

        TeachMain tm = new TeachMain();
        tm.name="uzzal";
        tm.age = 21;
        tm.subTeach="ICT";
        tm.showRes2();
    }
}

*************************************************
step : 2


package OOP;

public class TeachMain extends Person {

        //name , age, display method come to TecMain reason of extends ..

        String subTeach ;

        void showRes2(){
        System.out.println(subTeach);
        display();
    }


}


*************************************************

step : 03

package OOP;

public class Person {

    String name;
    int age;


    void display(){

        System.out.println("Name :"+name);
        System.out.println("Age :"+age);

    }
}

OOP : 28
Instance of operator.

1.	Object – instance;

Coding

public class InheritMain {



public static void main(String args[]) {



Animal a = new Animal();

Person p = new Person();

Teacher t = new Teacher();



System.out.println(a instanceof Animal);

System.out.println(p instanceof Animal);

System.out.println(t instanceof Person);

System.out.println(t instanceof Animal);

System.out.println(p instanceof Teacher);





}

}



********************************

step- 2

package OOP.Inheritance2;



public class Animal {









}

************************

3

package OOP.Inheritance2;



public class Person extends Animal {





}



***********************************************

step- 4

package OOP.Inheritance2;



public class Teacher extends Person {



String name;

int age;

}




# OOP 29 
# Inheritance Private Member
1.	 Discuss to how to private member inherit.

2.	 Honestly any class er private num inherit kora jaina. Cause , private mane oi class er jonno.  resection do it.

3.	But possible , setter and getter er maddhome amara oi class er access nite parbo. But, private gulo amara access nite parina.\

Coding: 

o/p  Name Uzzal
Age 20
qualification BSC In CSE

Name Suzal
Age 20
qualification BSS

//step : 01
package OOP.InheritPrivate;

public class Person {

   private String name;
   private int age;

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public int getAge() {
        return age;
    }

    public void setAge(int age) {
        this.age = age;
    }
}

*************************************************
step : 02
package OOP.InheritPrivate;

public class Teacher extends Person {

    // name age;

    String qual;


    void display(){

        System.out.println("Name "+getName());
        System.out.println("Age "+getAge());
        System.out.println("qualification "+qual);
        System.out.println();
    }

}
**********************************************
step : 03


package OOP.InheritPrivate;

public class IPMain {

    public static void main (String args[]){

        Teacher t1 = new Teacher();
        t1.setName("Uzzal");
        t1.setAge(20);
        t1.qual="BSC In CSE";
        t1.display();

        Teacher t2 = new Teacher();
        t2.setName("Suzal");
        t2.setAge(20);
        t2.qual="BSS";
        t2.display();



    }

}
















# OOP – 30
# Types of Inheritance:







         






b->A  , c->b, c->a, 







Sob gulo class A class ke inherit korbe that’s means 




       Multiple  inheritance java support korena.










# OOP  - 31
# Method Overriding

1.	Relation of method

2.	Method overloading – same name method, differ return type, differ to parameter.
3.	Method Overridding – same name method, same name parameter, same return type. 

4.	Overriding- must be declare inheritance that’s for use extends . call of method overriding.   
 
5.	If you don’t declare extends that’s don’t call method overriding.


6.	Inheritance na hole method overriding hobei na.

7.	Declaring method in subclass which is already present super class that’s means Method Overriding.


8.	Sub class , super class present are same method name that’s call method overriding 

9.	Method relation an Object .           Static keyword relation a class 
Method overriding flexible:-
1.	Code reuse
2.	One interface, multiple implement
3.	Run time polymorphism.

overriding code:- 

1.	Static method override korte parbona.

2.	Main method static e jonno override korte parbona. 

3.	Just create user method override



o/p: 

Name : uzzal
Age : 20
Qualification : BSC In CSE

Name : Suzal
Age : 22
Qualification : BSS


step: 01

package OOP.MethodOverridding;

public class Person {

    private String name;
    private int age;

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public int getAge() {
        return age;
    }

    public void setAge(int age) {
        this.age = age;
    }

    void displayInfo(){

         System.out.println("Name :"+name);
         System.out.println("Age :"+age);
     }


}
***********************************
step: 02

package OOP.MethodOverridding;

public class Teacher extends Person {

    String qualification;


@Override
    void  displayInfo(){

        System.out.println("Name : "+getName());
        System.out.println("Age : "+getAge());
        System.out.println("Qualification : "+qualification);
        System.out.println();
    }
}

****************************************
package OOP.MethodOverridding;

public class MethodMain {

    public static void main(String args[]){

        Teacher t1 = new Teacher();
        t1.setName("uzzal");
        t1.setAge(20);
        t1.qualification="BSC In CSE";
        t1.displayInfo();


        Teacher t2 = new Teacher();
        t2.setName("Suzal");
        t2.setAge(22);
        t2.qualification="BSS";
        t2.displayInfo();




    }
}

# OOP -32
# Method overloading & Method Overriding

















Overloading:- 
1.	 Overloading ghote single akta class a.
2.	Overloading a parameter must be differ.
3.	Inheritance extends noy.
4.	Return type matter noy.

Over ridding:-
1.	 Overriding hoy at least 2 ta class er moddhe akta super class & sub class. Parent class & base class.
2.	 Overriding parameter must be same.
3.	 Inheritance extend must .
4.	Return type must be same.








Multiple Inheritance
 





# OOP – 33
# Super Class use to call instance Variables
1.	Super class using kora hoy , method variable, constructer  a gulo ke refer korar jonno.
  

Java OOP-34
Super Class use to call Method
1.	Super method ke call korte hole , at first super class ti use korte hobe.
2.	 Simple method er jonno super keyword projon nei
3.	

 












# Java OOP -35
Super class use to Call Constructer

1.	Super constructer call dibo , tai constructer create korte hobe.
2.	 Parent class er constructer a  - super();








# OOP - 36
Super keyword
1.	Supper keyword to first  create a constructer.
2.	Constructer call using super();
3.	Method overriding
4.	Method overriding call to constructer();

Codding super keyword , constructer, super , method overriding:---                                 
o/p

Name Uzzal

Age 15

Department : English

Name Suzal

Age 25

Department : JMI

*******************************

step: 1



package OOP.SuperClass;



public class Person {

String name;

int age;

//create constructer

Person(String n, int a){

name = n;

age = a;

}





//create user method;

void display(){

System.out.println("Name "+ name );

System.out.println("Age "+ age );

}



}





******************************

step : 2

package OOP.SuperClass;



public class Teacher extends Person {
String dept;
//create a constructer

Teacher(String n, int a, String d){

//call to super class

super(n,a);

dept = d;

}



// call to method override

@Override

void display(){

super.display();

System.out.println("Department : "+dept);

System.out.println();

}



}



***********************************

step: 03

package OOP.SuperClass;



public class MainSuper {



public static void main(String args[]){



//call to obj create

Teacher t1 = new Teacher("Uzzal",15,"English");

t1.display();



Teacher t2 = new Teacher("Suzal",25,"JMI");

t2.display();

}
# OOP – 37
This keyword ();

1.	 Local variable priorty beshi tai instance variable hide korar jonno , instance variable er age this keyword kora jai. this.name = name;
2.	 Constructer create korar por , uporer parameter Jodi same hoy tahole super keyword moton this keyword use kora jai, 
Ex: - this(parameter name bolte hobe);
OOP – 38
Final keyword
1.	Final keyword er maddhome jeta kora hoy user k restic kora hoy.











2.	Final keyword final korle not changeable. Variable er age final declare korle ar change kora jabena.







                              Final Variable
 
Final variable: - 
1.	final hishabe Jodi kono variable aponi declare koren tahole seta r change / modify kora jabena. 
2.	Final variable name always capital letter hobe.
3.	Final variable sorasori initlize kora jai ex: final String UNI_NAME = “DIU”




Blank Final Variable:-

1.	J Variable sorasori initialize kora hoyni take blank final variable bola hoy.
Ex: final UNI_NAME ;
2.	Blank final variable declare korte hobe constructer er madhome.
Ex: Teacher(){
      UNI_NAME=”KU”;
}

Static Final Variable:-
1.	Ei variable declare korte hobe static final variable er moddhe. Initialize korar jonnno amake static keyword use korte hobe.
Ex:  static final int fees;


2.	Obosshoi static keyword er moddhe use initialize korte hobe.
Ex: static {
	Fees=50;
}


Final keyword last
1.	Final method inheritance a override kora possible noy.
2.	Final method inherit kora jabe but override kora jabena.
3.	Final class ke inherit kora jabena.
1.	Yes we can inherit final method. But we can’t initialize override method
2.	Blank variable can’t initialize, if I initialize doing in constructer.
3.	Variable name declare static with final. But there is no initialize. this call of static final variable.
4.	Static method declare  with static block. Static{ }

# OOP – 39 
# POLYMORPHISM

# Polymorphism   hose amon akta mechanisom , jekhane parent class er ref value k sub class er object gulo ke ref korte pare.


1.	Polymorphism are 02 type:
#compile type / static type
#run time / dynamic 

2.	Compile type: - 
Method er  overload say 03 version type. Compiler ki korbe ? jokoni se complie korbe tokon se decide korbe kon method ta ke call korbe , e jonno eke bola hoy compile type polimorphism
# Method overloading
#constructer overloading




3.	Runtime / dynamic polymorphism 
         # Method overriding.






# super class er variable er moddhe sub class er object rakhte parbo. 
Ex:-       Person t = new Teacher();
This call by dynamic dispatch.










# OOP -39
# Run time Polymorphism

public static void main(String args[]){
    /*
    1. Polymorphism is a machanisam, parent class er Reference value Sub class,
       er object gulo ke reference kore..
  Overloading - Compile type - static type. - Method overloading, Constructor Overloading.
  Overriding - Run time - Dynamic type - Method overriding. 
               Parent class er variable gulo sub class a rakhte parbo. :)
               Must be overriden. 
     */

    // method overriding Polymorphism //Runtime Polymorphism // dynamic polymorphism

    // create a all class object...
    Person p = new Person();
    p.displayInfo();

     p = new Teacher();
     p.displayInfo();

     p = new Student();
     p.displayInfo();
}




Polymorphism
public static void main(String args[]) {

    // create a all class object..

    //create a array..
    Shape s[] = new Shape[3];

    //create a array index.
    s[0] = new Shape();
    s[1] = new Rectangle(10, 20);
    s[2] = new Triangle(20, 30);


    /*
    Shape s1 = new Shape();
    Shape s2 = new Rectangle(10, 20);
    Shape s3 = new Triangle(15, 25);
     */


    //call to method of for loop
    for (int i=0; i<3; i++){
        System.out.println(s[i].area());
    }


    // call to area method
    /*
    System.out.println(s1.area());
    System.out.println(s2.area());
    System.out.println(s3.area());
     */



# OOP – 40
# Java Abstraction
# Implementation  ti hiding thakbe , functionality ta user ke show korbe  - this call Abstraction. 
# 02 type of java abstraction: 
1.	Abstract class (0 to 100%) user wish
2.	Interface (100%) fully abstraction.






# Abstract class: 
# Must be declare before the class abstract.







#Abstract Method
Must be declare before the method abstract.

1. Abstract method has no body,
2. it must be initialize abstract class.
3. must be overridden
4. can never be final static.
5. semiclone thakbe. Then method signature.




# Abstract Class:-
1.	abstract class er moddhe non abstract method & abstract method 02 toi thakte parbe. Ei jonno puropuri abstract kora possible.
2.	 Non abstract class er moddhe abstract method kisutei thakte parbena.
3.	Kono method abstract declare korle class o abstract declare korte hobe.দ



# implementation:-
1.	send message method ti ke Rahim and Karim 02 joni extends korbe.
2.	Jokon Rahim and Karim method ti ke extends korbe tokon must be create overridden method .
3.	Class er vitore abstract method tahakle must be overridden.
4.	 Overridden Jodi na kora hoy , tahole class tike abstract declare korte hobe.

example:- 1









Example: 2
1.	 Abstract Classer object make kora jaina just create a reference. 
2.	 Super class er reference variable make kora jai,  ebar ei supeer class er reference variable dara sub class er obeject gulo ke refer kora jabe.






Abstract rules: - 
1.	Kono classer age abstract keyword dile abstract class

2.	Abstract class er object declare kora jabena.

3.	Abstract classer abstract method & non abstract method thakte pare.


4.	Jodi kono abstract class extends kori , tahole abstract class er sobgulo method overridden korte hobe.
5.	 Jodi overridden na kori tahole sei class er abstract declare korte hobe.

# OOP – 41
# Abstract Class practical
https://gist.github.com/uzzalmondalcse/b6aae97558da987dffc368804e7bf743




# OOP – 42
Interface
1.	 Interface is a fully abstract.
2.	 An Interface is a collection of abstract method;
3.	 Interface a just declare to abstract method , don’t alow this non abstract method.
4.	That’s call fully abstract. 
Why do need Interface
1.	 Fully abstraction, 
2.	It’s support for multiple inheritance.

Interface class & Mehod: 
1.		If you declare to before the class name interface this call by interface , class.
2.	  	Method must be Abstract , so If we want to write in class method .  This your method by default 
Public abstract void eat ();











3.	 Inter face variable: - 

Interface er variable must be constant saileo amara eta edit korte parina. Automatically public static final dhore nai. Instance v noy.
Important to tricks: - 
similar to extends , other’s implements..


1.	Interface er object make kora jaina.
2.	 Abstract class er object make kora jai.

Important : 
1.	 Akta Interface  akta class ke implements kore. Akon class er moddhe interface er signature ti fully method must be declare to class.

2.	 Interface and  class using to main method, must be class er  object use korte hobe. or initialize to main method. 


3.	 There is no chance create an interface object declare..

Code: 

Create a interface:- 
package OOP.Inheritance2;

public interface Doctor {

    // create a signature

    void operation();
}

create a class
step: 1
package OOP.Inheritance2;

public class MaleDoctor implements Doctor {

    // must be use implements method();

    public void operation(){

        System.out.println(" Speciallist of  Headache ");
    }
}


step: - 2
package OOP.Inheritance2;

public class FemaleDoctor implements Doctor {

    public void operation(){

        System.out.println("Special Apendiside");
    }
}


Mian
package OOP.Inheritance2;

public class Main {

    public static void main(String args[]){

        // create to object
// interface doesn’t create an object..
        MaleDoctor m = new MaleDoctor();
        m.operation();


        FemaleDoctor f = new FemaleDoctor();
        f.operation();


    }
}




















# OOP – 43 
Class multiple inheritance support  korena.
Interface multiple inheritance support kore.

Class: - 
 

1.	 B, C   class er implementation ta kintuo already deoai ase. E jonno jokon akta class extends kore, class er jokon object ke call korbo, tokon se kakae call dibe, ei foo er jono akta implementation, ei foo er jonno akta implementation.  erokom tader implementation ta kintuo already deoa ase. 
2.	Se kake call korbe etai kintu se bujte parena , tai eke bola hoy executive problem ba damond problem.

Interface: - 




1.	 Interface ta just implementation ta deaoa tahkena just method er name thake, method er body thake  na , just mehod er signature ta thake.  D class jokon implemenst korbe tokon kintuo implemention  already deoa ase . akon Jodi new object create kori, tahole sorasori foo(), method ke call korte ba access korte parbo. 
2.	Interface kokonoi obj create kora jaina, must be declare to class in object.

Multiple Inheritance , Implements: - 

**********************************************
step -1


package OOP.InheritanceMultiple;

public interface A {

    public abstract void play();
}


**********************************************
step 2
package OOP.InheritanceMultiple;

public interface B {

    public abstract void play();
}



**********************************************
step 3

package OOP.InheritanceMultiple;

public class C implements A,B {

    public void play(){

        //implemention dite hobe must be akta
        System.out.println("Hello I am User from C class ");
    }
}


**********************************************
step  4

package OOP.InheritanceMultiple;

public class D implements A,B {


    @Override
    public void play() {

        System.out.println("Hello i am user form D class");
    }
}



**********************************************
step 5

package OOP.InheritanceMultiple;

public class TestMain {

    public static void main(String args[]){


        C c = new C();
        c.play();

        D d = new D();
        d.play();

    }
}



# OOP: 44
# Class and Interface

Class and interface similar formula:- 
1.	Interface and class define to any method..
2.	It has same file extension . java.
How interface different from class: - 

1.	 Class er object make korte parbo, but interface er object make korte parbona,

2.	Class a constructer declare kora jai, but interface a constructer decare kora jaina.

3.	Interface er sob gulo method by default abstract, but class er method abstract / non abstract 02 toi thakte pare..

4.	 Interface a instance variable declare kora jaina, variable ti constant – change kora jaina. Class a instance a variable declare kora jai.

5.	Interface er maddhome multiple inheritace support kora jai, but class er maddhome multiple inheritance support kora jaina.










Interface vs Abstract Class: - - 












# OOP  : 45
Package Tutorial


1.	 Import jaba.util.* - all importer in call.
# Memory is not enough spaces.
2.	Akoi class er moddhe thakle object create kora jai.
3.	 But differ package er moddhe thakle object create kora jaina.
4.	 Akta package folder onno akta package folder object create korte saile firstly import.package name.class name
5.	Built in package class in java scanner.
6.	Import java.util package.
7.	Same class with in package name create a object but Package name are different you cannot access.
8.	If you want to access the class must declare to import other package.
 import.BItm.*;  









# OOP – 46
# Access Modifire

Public :- public declare korle akoi package  , class and other package use korte parbo. 
There is no problem show in session.


Private:- private declare korle oi class sara onno kono class a use kora jabena. ba access nite parbona. Obj declare korle error ashbe.

Protected: - protected declare korle oi class and oi package must use korte parbo .  but, Jodi  onno ba different akta package a jete hoy , tahole amader ei class er sathe onno package er class ke extends korte hobe.
Tar moddhe chole jabe and take call kore dibo.

Default:  default  declare korle oi class er package er moddhei simaboddhow thakte hobe. Orthat ,  packager moddhe class gulo assign korte parbo.  Onno kono package er class ke kono vabei use korte parbona.

Geeke for gives..web site search java t point.


/*
Private: - You have to declare to private keyword access to just this is Class,
Can't to assign Any class with any package ;
 */




/*
Public  - you have to declare to public keyword, access to any any class, with package.
there is restriction ..
 */

/*
Protected  - Same Package, same class. access to Protect member,
Onno package er sub class access to need must declare to extends keyword.

 */


/*
default : - just access  to packaging . 
 */

 



# OOP – 46
# Type Casting

Implicity type custing: - 


















	































Upcasting:- and down casting.
 


 





# OOOP 47(important)
# Anonymous class
Anonymous call hose amon akti class jar kono name ei thakbena.  To sei class kano use korbo. ?
Runtime er somoy kono akta class ba akta method ba akta interface er method  ke override korte chai.  Se khettre amder ei anonymous class help korbe. 
 
Then obj er maddhome display method call korle runtimer somoy update hobe…
# OOP – 48
# Exception and Handballing (week).
Exception: Run time a j error ta pai seta holo exception handballing.  Program make korlam make korar por kono error daklam na , but jokon run korbo , tokon Jodi error ta show korte chai tokon amake exception show korte hobe. 
Exception handaling tools:- 




1.	J code gulo exception dakha dite pare se code gulo try block er moddhe rakhbo.
2.	 Try block er moddhe Jodi kono exception dhora pore thole exception ta through korbe exception block er moddhe. 
3.	Multiple exception o rakhte pari..
4.	Finally block always kaj korbe.















 





 

# OOP- 49
# Decimal Number Formatting		

public class DecimalFormating {
    public static void main(String args[]){

        // dosomiker pore 2 ghor dakboo..
        double x = 2.9875488;
        System.out.printf("X = %.2f",x);

        System.out.println("");


        // java
        DecimalFormat db = new DecimalFormat("0.000");
        double d = 10.2564589;
        System.out.println("D :"+db.format(d));

    }






# OOP – 51
# To String (); (important)
Object class er method toString(); method ke call korte hobe.   Automatically overrite to  tostring method and method overriding.
package MasterOOPBestJava.ToString_43;

public class PersonMain {

    String name;
    int age;

    PersonMain(String name, int age){

        this.name = name;
        this.age = age;
    }

    // sokol class er top class holo object class.
    // sei class er akta method nissi toString();  - method.


    // built in method by toString();
    @Override
    public String toString(){

        return "Name : "+name+"\nAge : "+age;

    }





    public static void main(String args[]){

        PersonMain p1 = new PersonMain("Uzzal",23);
        PersonMain p2 = new PersonMain("Suzal",27);

        System.out.println("Name : "+p1);  // automatically call to to string method.
        System.out.println("Age : "+p2);



    }
}


# OOP – 52
# String comparison

Primitive data type err jonno -   == operator.
Object er jonno ba  - equals(); method use kora better.


 

equal()  -  string er content niye kaj kore. 02 string er moddhe tader original content niye kaj kore.


			






Equal operator (); - -using 
Equal() – method kaj korbe content niye 
=  =  equal operator kaj korbe reference niye.






# OOP – 53
# Link List(Important)

Array List : - Data store kore daynamic array er maddhome.
Array list :- ArrayList better for sorting and accessing data. 
1.	Link List – link list data store kore double link er madddhome.
2.	



















# OOP – 54
# Hash Map(Important)
Array and list gulo index er upore data store kore.
Hash map ki kore key valuer upore data store kore rakhe.  Akta key thakbe , key er under a akta value thakbe.




	


# OOP – 55
# Hash Set
Data gulo store  kora hoy hash table er maddhome. 
Hash set duplicate value niye kaj korena.





# OOP – 56
# Create file directory
 



file create a directory.. how to file created..







# OOP – 57
# How to written File




file delete and exist method call(); - 










# OOP: 58
# How to write into file..

How to Read file.










	 


