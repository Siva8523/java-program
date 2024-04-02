import java.io.*;
import java.util.*;
class Bank
{
    float getRateOfInterest()
    {
        return 0;
    }
}
class SBI extends Bank
{
    float getRateOfInterest()
    {
        return 8.4f;
    }
}
class ICICI extends Bank
{
    float getRateOfInterest()
    {
        return 7.3f;
    }
}
class AXIS extends Bank
{
    float getRateOfInterest()
    {
        return 9.7f;
    }
}
class DAY4BANKINTEREST
{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        String B;
        Bank b;
        float c;
        float d;
        float e;
        float f;

        b=new SBI();
        System.out.println("SBI Rate of Interest: "+b.getRateOfInterest());
        c= b.getRateOfInterest();
        b=new ICICI();
        System.out.println("ICICI Rate of Interest: "+b.getRateOfInterest());
        d=b.getRateOfInterest();
        b=new AXIS();
        System.out.println("AXIS Rate of Interest: "+b.getRateOfInterest());
        e= b.getRateOfInterest();
        System.out.println("Enter the bank name:");
        B=sc.next();
        System.out.println("Enter the ROI:");
        f=sc.nextFloat();
        if(f!=c&&f!=d&&f!=e)
        {

            System.out.println("RATE OF INTEREST IS INVALID");
        }
        if(B.equals("SBI") && f==c)
        {
            System.out.println("VALID");
        }
        if(B.equals("ICICI") && f==d)
        {
            System.out.println("VALID");
        }
        if(B.equals("AXIS") && f==e)
        {
            System.out.println("VALID");
        }
        if(!B.equals("SBI")&&!B.equals("ICICI")&&!B.equals("AXIS"))
        {

            System.out.println(" BANK NAME INVALID");
        }



    }
}
