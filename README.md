# case1
import java.util.Scanner;

public class casse 
{   public static void main(String[] args) { 

    Scanner sc=new Scanner(System.in);  
    int i=0;
    char arr[] = {'a','b','c','d','d','f','g','t','d','a'};
    for(char j:arr)
      {
        System.out.println(j);

      }
    System.out.println("Enter the character");
    char c = sc.next().charAt(0);
    for(char j:arr)
      {
        if (c == j)
        {
            i++;
        }

      }
    if (i == 0)
    {
        System.out.println("character not available");
    }
    else{
        System.out.println("Count of Character"+c+":"+i);
    }
    sc.close();

}
}
