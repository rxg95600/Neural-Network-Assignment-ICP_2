# Neural-Network-Assignment-ICP_2

NAME: RAMA KRISHNA GANTA ID#: 700759560

VIDEO:

1. Create a class Employee and then do the following
• Create a data member to count the number of Employees
• Create a constructor to initialize name, family, salary, department
• Create a function to average salary
• Create a Fulltime Employee class and it should inherit the properties of Employee class
• Create the instances of Fulltime Employee class and Employee class and call their member functions.

solution:
          This Python script demonstrate the basic employee management system using object-oriented principles. It defines an Employee class with private attributes (name, family, salary, department), a class variable to track the number of employees, and methods for calculating average salary and displaying employee data. The FulltimeEmployee class inherits from Employee, representing full-time staff. Employees are created in the main function, added to a list, and their average salary is computed using the average_salary() method. The program demonstrates encapsulation, inheritance, and object creation while showcasing basic employee management operations. 

output:

The count of an employee is: 4
Average salary of an employee is: 148750.0

2. Numpy
Using NumPy create random vector of size 20 having only float in the range 1-20.
Then reshape the array to 4 by 5
Then replace the max in each row by 0 (axis=1)
(you can NOT implement it via for loop)

solution:
          This Python script uses NumPy to create a random 4x5 matrix, identify the maximum value in each row, and replace it with a specified value (0 in this case). The replace_maxmium() function uses NumPy's where method to locate the maximum value along the specified axis and replaces it with the given value, while retaining other elements. In the main() function, a random vector of 20 numbers is generated, reshaped into a 4x5 matrix, and the maximum values in each row are replaced with zeros. This demonstrates array manipulation and conditional replacement using NumPy.

output:

[11.08042947 14.37411928  5.41447214 17.42042542 15.83981412 15.16986717
  6.74211054 18.47515711  6.34841565 18.46563753  6.17364994 11.80403328
  6.50543414  3.47420345  3.70013368  4.57851659 10.06643835 11.82047234
 15.56011057  3.59213294]


[[11.08042947 14.37411928  5.41447214 17.42042542 15.83981412]
 [15.16986717  6.74211054 18.47515711  6.34841565 18.46563753]
 [ 6.17364994 11.80403328  6.50543414  3.47420345  3.70013368]
 [ 4.57851659 10.06643835 11.82047234 15.56011057  3.59213294]]

 maximum value in each row replaced by zero
[[11.08042947 14.37411928  5.41447214  0.         15.83981412]
 [15.16986717  6.74211054  0.          6.34841565 18.46563753]
 [ 6.17364994  0.          6.50543414  3.47420345  3.70013368]
 [ 4.57851659 10.06643835 11.82047234  0.          3.59213294]]

