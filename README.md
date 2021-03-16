# Prelim-Exam
class Student
{

private int ID number;
private int hours;
private int points;
private static int lastStudentID;
 
 
public void showIDnumber()
{
System.out.println("ID Number is: " + IDnumber);
}
 
public void showHours()
{
System.out.println("Credit Hours: " + hours);
}
 
public void showPoints()
{
System.out.println("Points Earned: " + points);
}
 
public double getGradePoint()
{
return (double) (points / hours);
}
 
}
