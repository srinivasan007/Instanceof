# Instanceof
package myprog;

public class Insatnce 
{
	void display()
	{

		System.out.println("hai");
	}

}
class sub extends Insatnce
{
	public static void main(String args[])
	{
		Insatnce t1=new Insatnce();
		t1.display();
		Insatnce t2=new sub();
		//boolean s=t1 instanceof Insatnce;
		//System.out.print(s);
		if(t2 instanceof Insatnce)
		{
			System.out.println("i am instance");
			
		}
	
	else
	{
		System.out.print("i am sub ");
	}
	}
}

