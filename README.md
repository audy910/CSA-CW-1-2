# CSA-CW-1-2
Copied from textbook as assigned

1.1 - initials, printing out stuff

public class Roses
{
    //--------------------------------------------------------------------------------
    // Prints a poem (of sorts) on multiple lines.
    //
    public static void main (String[] args)
    {
        System.out.println ("Roses are red,\n\tViolets are blue ,\n" +
        "Sugar is sweet,\n\tBut I have \"commitment issues\", \n\t" +
        "So I'd rather just be friends\n\tAt this point in our" +
        " relationship");
    }
}




public class Countdown {
    
    //-------------------------------------------------------------------------------
    //Prints two lines of output representing a rocket countdown
    //-------------------------------------------------------------------------------
    public static void main(String args[]) 
    {
      System.out.print ("Three... ");
      System.out.print("Two... ");
      System.out.print("One.. ");
      System.out.print("Zero... ");
      
      System.out.println ("Liftoff!"); // appears on first output line
      System.out.println ("Houston, we have a problem.");
    }
}






public class Geometry 
{
    //--------------------------------------------------
    // Prints the number of sides of several geometric shapes.
    //--------------------------------------------------
    public static void main (String[] args)
    {
        int sides = 7; // declaration with initialization
        System.out.println ("A heptagon has " + sides + " sides");
        
        sides = 10; // assignment statement
        System.out.println ("A decagon has " + sides + " sides.");
        
        sides = 12; 
        System.out.println ("A dodecagon has " + sides + " sides.");
    }
}





public class TempConverter
{

public static void main (String[] args)
    {
    final int BASE = 32;
    final double CONVERSION_FACTOR = 9.0 / 5.0;
    
    int celsiusTemp = 24; // value to convert
    double fahrenheitTemp;
    
    fahrenheitTemp = celsiusTemp * CONVERSION_FACTOR + BASE;
    
    System.out.println ("Celsius Temperature: " + celsiusTemp);
    System.out.println ("Fahrenheit Equivalent: " + fahrenheitTemp);
    }
}




public class StringMutation 
{
    public static void main(String args[]) 
    {
      String phrase = new String ("Change is inevitable");
      String mutation1, mutation2, mutation3, mutation4;
      
      System.out.println("Original string: \" " + phrase + "\"");
      System.out.println("Sum of x+y = Length of string: " + phrase.length());
      
      mutation1 = phrase.concat (", except from vending machines.");
      mutation2 = mutation1.toUpperCase();
      mutation3 = mutation2.replace ('E', 'X');
      mutation4 = mutation3.substring (3, 30);
      
      System.out.println ("Mutation #1: " + mutation1);
      System.out.println ("Mutation #2: " + mutation2);
      System.out.println ("Mutation #3: " + mutation3);
      System.out.println ("Mutation #4: " + mutation4);
      
      System.out.println ("Mutated length: " + mutation4.length());
    }
}

