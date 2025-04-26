# cse111-lab-6-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cse111-solved-21/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;131307&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE111 Lab 6 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
Lab Assignment no: 6

Write a Student class to get the desired output as shown below.

1. Create a Student class and a class variable called ID initialized with 0.

2. Create a constructor that takes 4 parameters: name, department, age and cgpa.

3. Write a get_details() method to represent all the details of a Student

4. Write a class method from_String() that takes 1 parameter which includes name, department, age and cgpa all four attributes in string.

#Write your code here for subtasks 1-6.

s1 = Student(“Samin”, “CSE”, 21, 3.91) s1.get_details()

print(“———————–“)

s2 = Student(“Fahim”, “ECE”, 21, 3.85) s2.get_details()

print(“———————–“)

s3 = Student(“Tahura”, “EEE”, 22, 3.01) s3.get_details()

print(“———————–“)

s4 = Student.from_String(“Sumaiya-BBA-23-3.96”) s4.get_details()

# Write the answer of subtask 5 here

# Write the answer of subtask 6 here

#You are not allowed to change the code above

OUTPUT

ID: 1

Name: Samin

Department: CSE

Age: 21

CGPA: 3.91

———————– ID: 2

Name: Fahim

Department: ECE

Age: 21

CGPA: 3.85

———————–

ID: 3

Name: Tahura

Department: EEE

Age: 22

CGPA: 3.01

———————–

ID: 4

Name: Sumaiya

Department: BBA

Age: 23

CGPA: 3.96

5. Explain the difference between a class variable and an instance variable. Print your answer at the very end of your code.

6. What is the difference between an instance method and class method? Print your answer at the very end

Write the Assassin class so that the given code provides the expected output.

1. Create Assassin class

2. Create 1 class variable

3. Create 1 class method titled ‘failureRate()’

4. Create 1 class method titled ‘failurePercentage()’

5. Maximum success_rate is 100

[You are not allowed to change the code below]

# Write your code here

john_wick = Assassin(‘John Wick’, 100)

john_wick.printDetails()

print(‘================================’) nagisa = Assassin.failureRate(“Nagisa”, 20) nagisa.printDetails()

print(‘================================’) akabane = Assassin.failurePercentage(‘Akabane’, 10) akabane.printDetails()

Output:

Name: John Wick

Success rate: 100%

Total number of Assassin: 1

============================

Name: Nagisa

Success rate: 80%

Total number of Assassin: 2

============================

Name: Akabane

Success rate: 90%

Total number of Assassin: 3

Implement the design of the Passenger class so that the following output is produced:

The assumption is Bus base-fare is 450 taka. A passenger can carry upto 20 kg for free. 50 taka will be added if bag weight is between 21 and 50 kg. 100 taka will be added if bag weight is greater than 50 kg.

[You are not allowed to change the code below]

# Write your code here

print(“Total Passenger:”, Passenger.count) p1 = Passenger(“Jack”) p1.set_bag_weight(90) p2 = Passenger(“Carol”) p2.set_bag_weight(10) p3 = Passenger(“Mike”) p3.set_bag_weight(25) print(“=========================”) p1.printDetail()

print(“=========================”) p2.printDetail()

print(“=========================”) p3.printDetail()

print(“=========================”) print(“Total Passenger:”, Passenger.count)

Output:

Total Passenger: 0

=========================

Name: Jack

Bus Fare: 550 taka

=========================

Name: Carol

Bus Fare: 450 taka

=========================

Name: Mike

Bus Fare: 500 taka

=========================

Total Passenger: 3

Task 4

Implement the design of the Travel class so that the following output is produced: [You are not allowed to change the code below]

# Write your code here

print(“No. of Traveller =”, Travel.count) print(“=======================”)

t1 = Travel(“Dhaka”,”India”)

print(t1.display_travel_info())

print(“=======================”) t2 = Travel(“Kuala Lampur”,”Dhaka”) t2.set_time(23)

print(t2.display_travel_info())

print(“=======================”) t3 = Travel(“Dhaka”,”New_Zealand”)

t3.set_time(15) t3.set_destination(“Germany”)

print(t3.display_travel_info())

print(“=======================”)

t4 = Travel(“Dhaka”,”India”) t4.set_time(9) t4.set_source(“Malaysia”) t4.set_destination(“Canada”)

print(t4.display_travel_info())

print(“=======================”)

print(“No. of Traveller =”, Travel.count) Output

No. of Traveller = 0

=======================

Source: Dhaka

Destination:India

Flight Time:1:00

=======================

Source: Kuala Lampur

Destination:Dhaka

Flight Time:23:00

=======================

Source: Dhaka

Destination:Germany

Flight Time:15:00

=======================

Source: Malaysia

Destination:Canada

Flight Time:9:00

=======================

No of Traveller = 4

Task 5

Create an Employee Class that will have

● Two instance variable: name and workingPeriod

● A class method named employeeByJoiningYear():

o To create an Employee object by joining year for calculating the working period

o It will have two Parameter name and year

● A static method experienceCheck() to check if an Employee is experienced or not o It will take working period and gender as parameter o If an employee’s working period is less than 3, he or she is not experienced

[You are not allowed to change the code below]

# Write your code here employee1 = Employee(‘Dororo’, 3)

3

5

Dororo

Harry

He is not experienced

She is experienced

Task 6

Implement the design of the Laptop class so that the following output is produced

[You are not allowed to change the code below]

# Write your code here

lenovo = Laptop(“Lenovo”, 5); dell = Laptop(“Dell”, 7); print(lenovo.name, lenovo.count) print(dell.name, dell.count)

print(“Total number of Laptops”, Laptop.laptopCount)

Laptop.advantage() Laptop.resetCount()

print(“Total number of Laptops”, Laptop.laptopCount) Output

Lenovo 5

Dell 7

Total number of Laptops 12

Laptops are portable

Total number of Laptops 0

Task 7

Design Cat class for the following code to get the output as shown.

You have already solved this problem in assignment 4 using constructor overloading. Now, solve this again but this time DO NOT USE CONSTRUCTOR OVERLOADING.

Hint: You will have to use classmethods.

[You are not allowed to change the code below]

# Write your code here

print(“Total number of cats:”, Cat.Number_of_cats) c1 = Cat.no_parameter() c2 = Cat.first_parameter(“Black”) c3 = Cat(“Brown”, “jumping”) c4 = Cat(“Red”, “purring”) c5 = Cat.second_parameter(“playing”)

print(“=======================”) c1.printCat() c2.printCat() c3.printCat() c4.printCat() c5.printCat() c1.changeColor(“Blue”) c3.changeColor(“Purple”) c1.printCat() c3.printCat() print(“=======================”)

print(“Total number of cats:”, Cat.Number_of_cats) Output:

Total number of cats: 0

=======================

White cat is sitting

Black cat is sitting

Brown cat is jumping

Red cat is purring

Grey cat is playing

Blue cat is sitting

Purple cat is jumping

=======================

Total number of cats: 5

Task 8

Write a Cylinder class to get the desired output as shown below.

1. You will have to create a Cylinder class.

2. You will have to create 2 class variables.

3. Create a required constructor.

4. Write 2 class methods:

• One that takes the height first and then the radius and then swaps

• One that takes a string where the radius and height values are separated with a hyphen.

Write 2 static methods:

• One that calculates the area of a whole cylinder (formula: 2πr2 + 2πrh)

• Another that calculates the volume of a cylinder (formula: πr2h)

**Observe the output values carefully to understand how the radius and height values are changing.

[You are not allowed to change the code below]

# Write your code here

c1 = Cylinder(0,0)

Cylinder.area(c1.radius,c1.height)

Cylinder.volume(c1.radius,c1.height) print(“===============================”) c2 = Cylinder.swap(8,3) c2.area(c2.radius,c2.height)

c2.volume(c2.radius,c2.height)

print(“===============================”)

c3 = Cylinder.changeFormat(“7-13”) c3.area(c3.radius,c3.height)

c3.volume(c3.radius,c3.height)

print(“===============================”)

Cylinder(0.3,5.56).area(Cylinder.radius,Cylinder.height) print(“===============================”)

Cylinder(3,5).volume(Cylinder.radius,Cylinder.height)) Output:

Default radius=5 and height=18.

Updated: radius=0 and height=0.

Area: 0.0

Volume: 0.0

===============================

Default radius=0 and height=0.

Updated: radius=3 and height=8.

Area: 207.34511513692635

Volume: 226.1946710584651

===============================

Default radius=3 and height=8.

Updated: radius=7.0 and height=13.0.

Area: 879.645943005142

Volume: 2001.1945203366981 ===============================

Default radius=7.0 and height=13.0.

Updated: radius=0.3 and height=5.56.

Area: 11.045839770021713

===============================

Default radius=0.3 and height=5.56.

Updated: radius=3 and height=5.

Volume: 141.3716694115407

Task 9

Write the Student class so that the given code provides the expected output.

1. Create Student class

2. Create 3 class variable

3. Create 1 class method for object creation

4. Create 1 class method for printing

[You are not allowed to change the code below]

# Write your code here

Student.printDetails()

print(‘#########################’)

mikasa = Student(‘Mikasa Ackerman’, “CSE”)

mikasa.individualDetail()

print(‘——————————————‘)

Student.printDetails()

print(‘========================’)

harry = Student.createStudent(‘Harry Potter’, “Defence Against Dark

harry.individualDetail()

print(‘——————————————-‘)

Student.printDetails()

print(‘=========================’)

levi = Student.createStudent(“Levi Ackerman”, “CSE”) levi.individualDetail()

print(‘——————————————–‘)

Student.printDetails()

Output:

Total Student(s): 0

Other Institution Student(s): 0

################################

Name: Mikasa Ackerman

Department: CSE

—————————————————— Total Student(s): 1

Other Institution Student(s): 0

===============================

Name: Harry Potter

Department: Defence Against Dark Arts

—————————————————— Total Student(s): 2

Other Institution Student(s): 1

===============================

Name: Levi Ackerman

Department: CSE

—————————————————— Total Student(s): 3

Other Institution Student(s): 1

Task 10

Write the SultansDine class so that the given code provides the expected output.

[You are not allowed to change the code below]

# Write your code here

SultansDine.details() print(‘########################’) dhanmodi = SultansDine(‘Dhanmondi’) dhanmodi.sellQuantity(25) dhanmodi.branchInformation()

print(‘—————————————–‘)

SultansDine.details()

print(‘========================’)

baily_road = SultansDine(‘Baily Road’) baily_road.sellQuantity(15) baily_road.branchInformation()

print(‘—————————————–‘)

SultansDine.details()

print(‘========================’)

gulshan = SultansDine(‘Gulshan’) gulshan.sellQuantity(9)

gulshan.branchInformation()

print(‘—————————————–‘)

SultansDine.details() Output:

Total Number of branch(s): 0

Total Sell: 0 Taka

#################################

Branch Name: Dhanmondi

Branch Sell: 10000 Taka

—————————————–

Total Number of branch(s): 1

Total Sell: 10000 Taka

Branch Name: Dhanmondi, Branch Sell: 10000 Taka

Branch consists of total sell’s: 100.00%

================================

Branch Name: Baily Road

Branch Sell: 5250 Taka

—————————————–

Total Number of branch(s): 2

Total Sell: 15250 Taka

Branch Name: Dhanmondi, Branch Sell: 10000 Taka

Branch consists of total sell’s: 65.57%

Branch Name: Baily Road, Branch Sell: 5250 Taka

Branch consists of total sell’s: 34.43%

================================

Branch Name: Gulshan

Branch Sell: 2700 Taka

—————————————–

Total Number of branch(s): 3

Total Sell: 17950 Taka

Branch Name: Dhanmondi, Branch Sell: 10000 Taka

Branch consists of total sell’s: 55.71%

Branch Name: Baily Road, Branch Sell: 5250 Taka

Branch consists of total sell’s: 29.25%

Branch Name: Gulshan, Branch Sell: 2700 Taka

Branch consists of total sell’s: 15.04%

Subtaks:

1. Create SultansDine class

2. Create 2 class variable and 1 class list

3. Create 1 class method

4. Calculation of branch sell is given below

a. If sellQuantity &lt; 10:

i. Branch_sell = quantity * 300

b. Else if sellQuantity &lt; 20:

i. Branch_sell = quantity * 350

c. Else

i. Branch_sell = quantity * 400

5. Calculation of branch’s sell percentage = (branch’s sell / total sell) * 100
