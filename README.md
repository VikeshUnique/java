public class Student
{
    int rollno;
    String name;
    String mobileno;
    String emailid;
    Student(int a,String b,String c,String d)
    {
        rollno=a;
        mobileno=b;
        name=c;
        emailid=d;
        
    }
    void display()
    {
        System.out.println(rollno);
        System.out.println(mobileno);
        System.out.println(name);
        System.out.println(emailid);
    }
    public static void main(String[] args)
    {
        Student s1=new Student(56,"9087928738","Vikesh","vikiksr2003gmailcom");
        Student s2=new Student(1,"6380134983","Aarthi","aarthigomathi7gmailcom");
        s1.display();
        s2.display();

    }
}# java
