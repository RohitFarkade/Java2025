## Wrapper Class
    Java Uses Simple Wraper Class Store Information About Its Basic Primitive Data Type Like Int and String Etc Which Can't be Store inside the primitive data type itself it includes simple operation and basic Values like below
    Integer
    Eg. int integerMinimum = Integer.MIN_VALUE;
    (There are some values which we can retrive from Wrapper Class like Integer Which Stores MIN_VALUE   ,SIZE)

        Primitive	Wrapper Class
        byte	    Byte
        short	    Short
        char	    Character
        int	        Integer
        long	    Long
        float	    Float
        double	    Double
        boolean	    Boolean
### Note. Wraparound Simply means overflow or underflow
    Long Value Denotation For Readability ex long num = 100L or 100l its also compulsory when assginin  numeric literal larger than Intger max;


    casting Hieracrcy 
    byte->short->int->float->double reverse is not possible without casting
    defualt ->int & double (remeber to cast when assigning more precise value to float like
    float myFloat = 4.34; ->error;
    correct way:
    float myFloat = (float)4.56;
    or 
    float myFloat = 4.56f;
    )


    BigDecimal ->> when accurate precision is needed
    StringBuilder ->> when string needs to be mutable (as defualt string is immutable it creates new string whenever we append something to it)

    empty string literal ""
    used when concatenating two chars