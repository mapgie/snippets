# snippets
Visual Studio Snippets for C# Console apps
A collection of snippets I use in C#. 

Go to Tools > Code Snippet Manager > Add Folder, and add wherever you've saved the snippets to.
To use the snippets, type the keyword and use TAB twice.

**consolereadline.snippet** keyword _crr

>var input = Console.ReadLine();

**escapekey.snippet**      keyword _anykey

> Console.WriteLine("Press any key to exit.");
> Console.ReadKey(true);	

**stringToParse.snippet**  keyword _stip - meaning (S)tring (T)o (I)nteger (P)arse

> string stringToParse = "";
> int numberOut;

> while (!int.TryParse(stringToParse, out numberOut))
>			{
>			Console.WriteLine("Please type a number.");
>			stringToParse = Console.ReadLine();
>			};

