# Mathematical-Table
Java program for  creating mathematical table

class Table

{
	public static void main(String[] args) 
	{
		int i;
		Scanner sc = new Scanner(System.in);
		System.out.print("enter num=");
		int n=sc.nextInt();
		for (i=1;i<=10;i++) 
		{
			int num=n*i;
			System.out.println(n+"*"+i+"="+num);
		}
	}
