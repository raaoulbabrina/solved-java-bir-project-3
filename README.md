Download Link: https://assignmentchef.com/product/solved-java-bir-project-3
<br>
<strong>Assignment3: </strong>

Palestinian Dairy Factory

<u>Employee Class:</u>

Design a class named Employee . The class should keep the following information in fields:

lEmployee name.

lEmployee Number.

lHire date.

lAddress that composed of (street, state,city,zip code).

Write one or more constructors and the appropriate accessor and mutator methods for the class. This class has isEmpNumberValid method which return boolean data type .

Employee Number in the format XXX–L, where each X is a digit within the range 0–9 and the L is a letter within the range A–M

<u>ProductionWorker Class:</u>

Next, write a class named productionWorker that inherits from the Employee class. The productionWorker class should have fields to hold the following information:

lShift (an integer)

lHourly pay rate (a double)

lNumber of hours per month

The workday is divided into two shifts:day and night. The shift field will be an integer value representing the shift that the employee works. The day shift is shift 1 and the night shift is shift 2. getTotalSalary() method should calculate the total salary based on the following:

Day shift worker should at least works 8 hours with rate per hour, and for any extra hours he/she get 1.25 hours instead of it, but night shift have to work at least 7 hours and for any extra hours he/she get 1.5 hours instead of it. Day shifts has only one value, 1 or 2 and others not allowed. Calculation of salary should be per month.(let month has 26 days/work).

<em>Write one or more constructors and the appropriate accessor and mutator methods for the class</em>.

<u>ShiftSupervisor Class:</u>

In this factory, a shift supervisor is an employee whose supervises a shift. In addition to a basic salary, the shift supervisor earns a monthly bonus when his or her shift meets production goals (set this value by program user). Design a ShiftSupervisor class that inherits from the Employee class you created above. The ShiftSupervisor class should have a field that holds the following information:

lmonthly salary

lmonthly production bonus that a shift supervisor has earned.

lNumber of products that produced by team that he/she supervised. lNumber of products must produced under his/her supervision.

getTotalSalary() method should calculate the total salary based on the following: If shift

supervisor employee teams produce the required number of products or more, the he/she can earn the monthly bonus. <em>Write one or more constructors and the appropriate accessor and mutator methods for the class.</em>

<u>TeamLeader Class:</u>

In this factory, a team leader is production worker who leads a small team. In addition to hourly pay, team leaders earn a fixed monthly bonus (read from user). Team leaders are required to attend a minimum number of hours of training per month.

The TeamLeader class should have a field that holds the following information:

lMonthly Bonus

lRequired Training Hours

lTraining Hours Attended

Design a TeamLeader class that inherits from the ProductionWorker class you designed. getTotalSalary() method should calculate the total salary based on the following:

<ul>

 <li>Hours and payed rate +</li>

 <li>calculations of bonus depends on the total training hours attended by team leader according to the following equation. Bonus_achieved= Bonus*training _hours/attended_hours</li>

</ul>

<em>Write one or more constructors and the appropriate accessor and mutator methods for the class.</em>

<u>Notes :</u>

ltoString method should be implemented in appropriate way in all Employee sub classes displaying all the information including.

lYour program should be test for all bugs and illegal inputs from user.

lCreate classes separately (Employee.java,ProductionWorker.java,etc) l<u>You should decide the data types </u>for every data members in classes

<u>Competitive Part : </u><strong>You have to guess other methods,at least <u>one different </u>method for any class from above program.(These methods should be YOURS and not shared with others , every new unique creative method will get +3 marks as bonus ).This method should do something creative (calculation) , not accessor and mutator.</strong>

<strong>Class Driver for Palestinian Dairy Factory</strong>:

<ol>

 <li>Draw UML for this factory ( consider all notations, private, public, protected, final, for modifiers and methods, and relations like like inheritance and aggregations) .</li>

</ol>

<strong><em>You can use any tools that may helps in class diagram, covert to </em></strong><strong><em>pdf </em></strong><strong><em>format and attache it </em></strong><em>. I recommend to use free tool form </em><a href="https://www.diagrams.net/">https://www.diagrams.net/</a>

<ol start="2">

 <li>You should create a Test class that has an Arraylist of different Employee types, then call a method that will list all employee info who is greater than average of all employees.</li>

</ol>

public static void ListGreaterThanAverage(ArrayList&lt;Employee&gt; list)

{ …. }

<strong>Note: Array List should have at least 2 types from every subclass (fill the array list manually).You don’t need to create scanner to read from console </strong><u>Set of instructions:</u>

1.Create folder at your desktop with your Assignment#, ID, and your name Example:A3_1190100_AliMohammad

<ol start="2">

 <li>Create a new project using Eclipse IDE and store your project inside this folder.</li>

</ol>

3.<strong>Zipped </strong>this folder and submit it by your ITC account [under meta course ].