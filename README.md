# snippets
## Visual Studio Snippets for C# Console apps

This is a collection of snippets I use in C#. 
**To add to Visual Studio:** Tools > Code Snippet Manager > Add Folder
Add wherever you've saved the snippets to. To use the snippets, type the keyword and use TAB twice.


file | keyword | output
-----|---------|--------------------
**consolereadline.snippet** |   _crr_ 	 | ```var input = Console.ReadLine();```
**escapekey.snippet** 	    | _anykey_   | ```Console.WriteLine("Press any key to exit.");```<br>```Console.ReadKey(true); ```
**stringToParse.snippet**   | _stip_  (S)tring (T)o (I)nteger (P)arse_ | ``` string stringToParse = "";```<br>```int numberOut;```<br> ```while (!int.TryParse(stringToParse, out numberOut))``` <br>```{```<br>```  Console.WriteLine("Please type a number.");```<br> ```  stringToParse = Console.ReadLine();``` <br>```}```

-- @mapgiedev 
