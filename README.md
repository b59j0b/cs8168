java c
Java Lab 6
Fall 2021
In this lab, you will practice with classes.
1. Create a project named Lab6.    For each class   specification listed   in   the problems   2-5,   create   the   class   in   the   src folder. In addition to any other methods mentioned below,   each class   should   have   the   following   methods         (feel free to use IntelliJ to auto-generate these, see Code->Generate):
- default constructor
- one overloaded constructor for all   the   member   data
- getters and setters   for   all   member   data
- a toString( ) method. This should return a   formatted   string   containing the member   data   with   labels,   such   as   "minimum:   " + minimum, for the minimum data field in   Sensor.
2. Class   Sensor. Data: minimum, maximum, currentValue, interval – double; location, type –   String; id –   int.   Methods: boolean trip( ). This method returns true if   the currentValue is less than minimum   or   greater than maximum and returns false otherwise.
3. Class Device. Data: type, location – String; id – int. Methods:   void   actuate(   ).   This   method prints   the   formatted data (that is, it prints toString() )   in ALL   CAPS.
4. Class Room. Data: length, width– double; name – String; id –   int.   Methods:   double   getArea(   ).   This method   computes and returns the room's area.
5. Class Alarm. Data: message – String; id -int. Methods: void   soundTheAlarm(   ) –   displays the   message   and   simulates a   911   call.
6. Create a class called Lab6; in it,   create   a   main   method   the   does   the   following:
- create a   Sensor object代 写Java Lab 6 Fall 2021Java
代做程序编程语言 named temperature with data (in the   order   listed   above):   0.0,   120.0,   68.0,   1.0,   kitchen,   temperature, id   1.
- create a Device object named extinguisher with data   fire   extinguisher, kitchen,   1.
- create a Room object named kitchen with data   12.0,   15.0, kitchen,   1.
- create an Alarm object named bell with data   "Ding! Ding!",   1.
- display all the objects by printing their toString( ).
7. Continue with main:
Display a welcome message. Display the Room information (yes, again).
Create a loop that asks the user if   they want to enter   a new value,   Y   or N;   loop until they   enter N.   In the   loop,   show the current kitchen temperature and prompt the user enter a new temperature; use it to   reset   the   temperature object's currentValue, then see if   that tripped the sensor – if   it   did,   actuate   the   extinguisher,   then sound the alarm; then reset the kitchen temperature back to what it was.8. There are four related classes. How should they be   organized? And   how   should   they   communicate   with   each other? Write your answer as a comment   at the   end   of   main( );   include   in   it:   (a.)   why   you   decided   on   this organization, and (b.) how the communication in main's loop would   occur – which object/method would   main   call, then which object/method would that call, to get all the   same work done.
Deliverable: Add your name and Andrew id to the comment at the top   of   the Lab6   class   file.   Zip   all   the   .java   files and upload it to   Canvas.







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
