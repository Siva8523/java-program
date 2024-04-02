import java.util.*;
 class large 
{
 public static void main(String[] args) 
{
try{
 Scanner input = new Scanner(System.in);
 System.out.print("enter the size of the array:- ");
 int size = input.nextInt();
 int[] arr = new int[size];
 System.out.println("enter the values in the array:- ");
 for(int i=0;i<size;i++){
 arr[i] = input.nextInt();
 }
 Arrays.sort(arr);
 System.out.print("enter the Mth largest number:- ");
 int m = input.nextInt();
 int max=0;
 if(m<=0)
 System.out.println("please enter the valid input");
 else{
 max = arr[arr.length-m];
 System.out.println("the largest number is "+max);
}
 }
catch(Exception e)
{
    System.out.println("Invalid due to string or float size or value");
}
}
 }
