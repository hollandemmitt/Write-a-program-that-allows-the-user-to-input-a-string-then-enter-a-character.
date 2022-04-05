# Write-a-program-that-allows-the-user-to-input-a-string-then-enter-a-character.
Write a program that allows the user to input a string, then enter a character.
import java.util.Scanner;
public class BaiTapJavaCoBan16
{
    public static void main(String[] args)
    {
       String String;
       char kiTu;
       boolean tonTai = false;
       Scanner sc = new Scanner(System.in);
   
       System.out.println("Enter a string: ");
       string = sc.nextLine();
       System.out.println("Enter the character you want to check:");
       kiTu = sc.nextLine().charAt(0);
   
       char mangKiTu[] = chuoi.toCharArray();
       for (int i = 0; i < mangKiTu.length; i++)
       {
          if (kiTu == mangKiTu[i])
          {
             System.out.println("Yes");
             tonTai = true;
          }
       }
       if(tonTai == false)
       System.out.println("No");
    }
}
