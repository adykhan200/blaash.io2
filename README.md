using System;
 
public class GFG
{
    public static void Main(String[] args)
    {
		String s = Console.ReadLine();
		string[] str = s.Split(' ');
		int m=Convert.ToInt32(Console.ReadLine())-1;
		int n=Convert.ToInt32(Console.ReadLine())-1;
		if(m>str.Length||n>str[m].Length||m.Equals(0)||n.Equals(0))
		{
			Console.WriteLine("Wrong input");
		}
		else
		{
		Console.WriteLine(str[m]);
		Console.WriteLine(str[m][n]);
		}
    }
}
