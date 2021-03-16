# Prelim-Exam
  class ShowStudent
{
// the private data members
private int IDnumber;
private int hours;
private int points;
private static int lastStudentID;
 
// the public get and set methods
 
public void setIDnumber()
{
lastStudentID += 1;
IDnumber = lastStudentID;
}
 
public int getIDnumber()
{
return IDnumber;
}
 
public void setHours(int number)
{
hours = number;
}
 
public int getHours()
{
return hours;
}
 
public void setPoints(int number)
class ShowStudent
{
public static void main (String args[])
{
Student student = new Student();
 
student.setHours(Integer.parseInt(args[0]));
student.setIDnumber();
student.setPoints(Integer.parseInt(args[1]));
student.showIDnumber();
student.showPoints();
student.showHours();
System.out.println("The grade point average is "
+ student.getGradePoint());
System.out.println(" ");
 
Student student2 = new Student();
student2.setHours(Integer.parseInt(args[2]));
student2.setIDnumber();
student2.setPoints(Integer.parseInt(args[3]));
student2.showIDnumber();
student2.showPoints();
student2.showHours();
System.out.println("The grade point average is "
+ student2.getGradePoint());
System.out.println(" ");
 
Student student3 = new Student();
student3.setHours(Integer.parseInt(args[4]));
student3..setIDnumber();
student3..setPoints(Integer.parseInt(args[5]));
student3..showIDnumber();
student3..showPoints();
student3..showHours();
System.out.println("The grade point average is "
+ student3..getGradePoint());
System.out.println(" ");
}
}
