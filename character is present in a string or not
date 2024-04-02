import java.util.Scanner;
public class Main
{
    public static void main(String args[])
    {
        Scanner input=new Scanner(System.in);
        System.out.print("Enter the string: ");
        String s=input.nextLine();
        System.out.print("Enter the char: ");
        char c=input.next().charAt(0);
        int l=s.length();
        char ch[]=new char[l];
        for(int i=0;i<l;i++)
        {
            ch[i]=s.charAt(i);
        }
        int x=0;
        for(int i=0;i<l;i++)
        {
            if(c==ch[i]) {
                System.out.print(c + " is present at index: " + (i + 1));
                x++;
            }

        }
        if(x>=1)
            ;
        else
            System.out.print("character not found");
    }
}
