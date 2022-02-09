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
///////////////////////////////////////////////////////////////////////////////////
////////////////DAY 7////////////////////////////

package pack1;

  class Parent{
	  
	public void ass() {
		System.out.println("heii");
	}
}

 public class Acc {

	private  void display() {
		System.out.println("this is welcome class display method");
	}
	public static void main(String[] args) {
		
	      Acc wel = new Acc();
	         Parent p= new Parent();
                 	//wel.assign();
                 	wel.display();
}
}
///
package pack2;

import pack1.*; 
class Paren{
	  
	private void assign() {
	   System.out.println("hello");
   }
     
	void assi() {
		System.out.println("hello");
	}
   

}
public class Ac 
{ 
	public static void main(String[] args) {
		
		//Welcome wel= new Welcome(); 
		Ac hel= new Ac();
		//hel.assign();
		//hel.assi();
		hel.ass();
		
		//hel.display();
	}

	

}
