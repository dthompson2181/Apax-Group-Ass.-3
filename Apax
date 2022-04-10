/**Name: Jason Wang, Allyson Windell, Dequandre Span, Kayla Worrell, and Daniel Thompson
 * Date: April 6, 2022
 * Desc: An app that allows any user input to cut down on the same letters.
 */

using System;

namespace Group11_Apaxian
{
    class Program
    {
        static void Main(string[] args)
        {
            // String input to store user input
            string input = Console.ReadLine();
            //String last to store
            string last="";
            //Initialize variable count at 0, and as long as user input length entirety
            // is less than count, increase count by 1
            for (int count = 0; count < input.Length - 1; count++)
            {
                //If the current user input length does not equal the input length +1
                if (input[count] != input[count + 1])
                    last += input[count];
                //Add the value to var last
            }
            // Console will write out the entirety (index 0 to end) of the shortened word
            Console.WriteLine(last + input[input.Length - 1]);
            Console.ReadLine();
            //Prevents app from closing immediately when pressing entered
        }
    }
}
