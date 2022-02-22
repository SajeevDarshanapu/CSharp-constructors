# CSharp-constructors

1)Constructor is a special method  that is used to intialise objects
2)It can be used to set intial values for fields

Advantages:
1)It is called when an object of a class is created
2)Constructor name must match the class name
3)It cannot have a return type(like void or int)

--------------
 class drum
    {
    public string brand;
    public string colour;
    
    public drum()
    {
        brand="Tama";
        colour="Purple";
    }
    static void Main(string[]args)                        
    {
        
        drum Object = new drum();
        Console.WriteLine(Object.colour);             //out: purple
        Console.WriteLine(Object.brand);              //out: Tama
    }
    }
