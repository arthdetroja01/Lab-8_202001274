# Lab-8_202001274
Lab 8 Software Engineering

## Lab-8 Unit Testing JUnit

### Arth Detroja 202001274

#### Goal:
The goal of this lab is to learn how to use JUnit to write unit tests for Java programs.


A software testing technique called "unit testing" tries to confirm the accuracy of the tiniest testable unit, or "unit," of code in an application. It entails evaluating the behavior of particular pieces of code, such as functions or methods, apart from the rest of the program. Before each piece of code is incorporated into the bigger program, this procedure is done for each individual unit.

Unit testing, to put it simply, is the process of dividing a software application into smaller, testable components and ensuring that each one functions well on its own before being integrated. This enables programmers to identify faults as they arise and repair them before they have a chance to worsen.

The number of errors that can be introduced throughout the software development process is reduced thanks to unit testing, which is a crucial step in the process. Developers can quickly find problems and solve them before they influence other parts of the software by testing each unit of code separately. In turn, this lowers the cost of correcting defects and guarantees a higher-quality end result.

## Lab Exercises

### Create a new Eclipse project, and within the project create a package:


<div align="center">
  <img src="https://user-images.githubusercontent.com/84059984/233594142-cf7e6f78-9558-4b6c-b45f-ff9e5bfedfcc.png">
</div>
<br>

### Create a class for a Boa. Here’s the code you can use (you may copy/paste):


<div align="center">
  <img src="https://user-images.githubusercontent.com/123644401/233321433-6aa86081-39a7-4a58-94fc-8820d4226414.png">
</div>
<br>

### Creating a JUnit Test Case class in Eclipse with methods isHealthy and fitsInCage:


<div align="center">
  <img src="https://user-images.githubusercontent.com/123644401/233321629-9ab526c8-1a76-47b7-9863-591a4ae373a9.png">
</div>
<br>

### Creating a setup method and annoting it with @before and creating jen and ken objects of boa class:


<div align="center">
  <img src="https://user-images.githubusercontent.com/123644401/233326530-89364ab3-0ddd-4469-8d67-886dc2d7ad95.png">
</div>
<br>

### Creating the test cases for testFitsInCage and testIsHealthy method:


<div align="center">
  <img src="https://user-images.githubusercontent.com/123644401/233325150-4c08b49e-3e70-4fa0-aeb7-dcad5954ceb6.png">
</div>
<br>

### Result of running 2 test cases:


<div align="center">
  <img src="https://user-images.githubusercontent.com/123644401/233325272-7abe171f-73d2-45a9-a5bc-d5f8986b073b.png">
</div>
<br>

### Writing the tests for length in inches:


<div align="center">
  <img src="https://user-images.githubusercontent.com/123644401/233322495-b75330ce-e4c4-4712-b46b-fe0fbb909923.png">
</div>
<br>

### Result of running all the test cases:


<div align="center">
  <img src="https://user-images.githubusercontent.com/123644401/233322628-00fc3cf1-4cb8-4a11-b235-29ac624f153f.png">
</div>
