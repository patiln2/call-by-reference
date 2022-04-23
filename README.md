using System;
namespace CSharp_Shell
{
	public class program
	{
		void get(ref int x)
		{
			x=10;
			Console.WriteLine(x);
		}
		public static void Main()
		{
			int x=20;
			program p=new program();
			Console.WriteLine("before function call:->"+x);
			p.get(ref x);
			Console.WriteLine("after function call:->"+x);
		
		}
		}
	}
