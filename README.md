# mycoding

package javaapplication5;

public class JavaApplication5 
{
    public static void main(String[] args)
    
    {
        int left,right;
        String s1 = "my name is rakesh";
        char[] temp= s1.toCharArray();
        System.out.println("before string is: "+s1);
         int l=s1.length();
         System.out.println(l);
         right=l-1;
         char temps;
         for(left=0;left<right;left++,right--)
         {
            temps=temp[left];
            temp[left]=temp[right];
            temp[right]=temps;
         }
         System.out.print("reverse string is: ");
         for (char c:temp)
         {
            System.out.print(c);
         } 
    }
}
