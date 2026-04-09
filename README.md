# EXP-6
EXP - 6 SIMULATION OF MEAN AND VARIANCE USING SCILAB

AIM:

To write a program for mean, variance and cross correlation in SCILAB and verify the output.

EQUIPMENTS Needed

•	Computer with i3 Processor
•	SCI LAB

Algorithm

1.	Define	the	Function:	Specify the	function	you	want	to	simulate.	For	example, f(x)=sin⁡(x)f(x) = \sin(x)f(x)=sin(x) or any other function.
2.	Generate Sample Points: Decide on the range and the number of sample points. Generate these sample points within the desired range.
3.	Evaluate the Function: Compute the function values at each of these sample points.
4.	Compute Mean, Variance and Cross Correlation: Use Scilab's functions to calculate the mean and variance of the computed function values.
5.	Display Results: Output the computed mean variance and Cross Correlation

PROCEDURE

•	Refer Algorithms and write code for the experiment.
•	Open SCILAB in System
•	Type your code in New Editor
•	Save the file
•	Execute the code
•	If any Error, correct it in code and execute again
•	Verify the generated results

PROGRAM
```
function X=f(x),
    z=3*(1-x)^2,
    X=x*z
a=0;
b=1;
function Y=c(y)
    z=3*(1-y)^2,
    Y=y*z
disp(EX,"i)Mean of X =")
disp(EY,"Mean of Y =")
function X=g(x),
    z=3*(1-x)^2,
    X=x^2*z
a=0;
b=1;
function Y=h(y)
    z=3*(1-y)^2,
    Y=y^2*z
EY2=intg(a,b,h);
vX2=EX2-(EX)^2;
vY2=EY2-(EY)^2;
disp(vX2,"ii)Variance of X");
disp(vY2,"Variance of Y");
x= input("type in the reference sequence=");
y= input("type in the second sequence="); 
n1=max(size(y))-1;
n2=max(size(x))-1;
r=corr(x,y,n1);
plot2d3('gnn',r);
```

OUTPUT

i)	Mean of X =	0.25 Mean of Y =	0.25

ii)	Variance of X	 0.0375 Variance of Y	0.0375

TABULATION

![WhatsApp Image 2026-04-10 at 02 18 41](https://github.com/user-attachments/assets/9df21e6b-4965-4f79-bc27-213d865d2647)



